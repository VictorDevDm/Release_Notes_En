# Automatic App Service Restart

**US ID: US-NPD-8126**

The app now includes a feature that ensures its services are automatically restarted to maintain continuous communication. If the device loses network connection, the system sends a command to restart these services. If communication is not reestablished within 1 hour, the command will be sent again, ensuring the app continues to function without interruptions.