# BasicWebServer

This WebServer replaces the standard Arduino WebServer.
With this version it ist possible to switch between WiFi and Ethernet (by Cable)
The Switch is implemented by a global #define Statement

#define USE_ETH   --> use ethernet library

#undef  USE_ETH   --> use WiFi library

