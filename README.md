# Hubitat_Delta_Faucet
Hubitat Driver Code for Delta Faucet

This driver was built using OpenAI based on the script found here:
https://gist.github.com/velaar/4e18a200c1db7b06109a3fd840838684

Thanks to all from the Hubitat community that participated in its creation!  More information here:
https://community.hubitat.com/t/integration-to-delta-voiceiq/119842?u=sebastien

Requirements: 

2 Secrets:
Both can be retrieved from https://device.legacy.deltafaucet.com/#/home

* delta_device_id - click on usage - it will be in the URL https://device.legacy.deltafaucet.com/#/device/usage/<your_device_id_here>
    delta_device_id: <your device id>
* delta_token 
    Go to inspector (Ctrl + Shift + I) -> Console;
    Type window.localStorage.auth_token a long string will come up. delta_token should be compiled as follows: 
       delta_token: Bearer <the string from above without quoted>
