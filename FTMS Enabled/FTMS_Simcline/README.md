# Changelog nRF52 FTMS Simcline

## v0.2.0

### Added or Changed
- Extra waiting directly after client connection, delay(poll_delay) moved after debug prints....
- Inserted full HBM support
- Corrected versions of client_enable and client_connect
- Corrected version of Indoor Bike Data
- updated with code of Client version 3.0
- Inserted setTxPower(4) after Bluefruit.begin() for scanning that was missing....
- Inserted Bluefruit.configCentralConn for central and peripheral
- Inserted Bluefruit.getName for determining the board name!
- changed filterRSSI to -80
- After Client or Server disconnect: scanning and advertising again!!
- Machine Status and Trainingstatus added missing if(...Chr.notifyEnabled)
- Inserted wait for connection in client_connect_callback 

## v0.2.1

### Added or Changed
- Corrected unsecure use of sizeof() with string arrays! Feature: FTM, CP and CSC !!!

## v0.2.2

### Added or Changed
- Phone upload with Server_Sends_NUS_TXD_Persistent_Settings realized after Central CCCD Notify enabled on NUS_TXD
- Trainer.IsConnected = true only at the end of client_connect_callback to avoid cluttering of messages
- Inserted more selective setting of Connection Parameters at start of scanning and at start of advertising
- Inserted requestConnectionParameter after client connection and synch with poll_delay
- Inserted #define REQUEST_NEW_CONNECTION_PARAMETERS and allows for selective setting of ConnectionInterval
  
# Changelog ESP32 FTMS Simcline

## v1.0.0

### Added or Changed
- Added this changelog :)

### Removed
- Some older versions