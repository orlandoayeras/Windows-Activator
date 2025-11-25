# Windows-Activator
Batch file to easily activate Windows using KMS server.

Guide:
Option 1 - Run the batch file.

Option 2 - For manual steps:

Step 1: Install the KMS Client Key
Run the command:
`slmgr /ipk <yourlicensekey>`

Replace <yourlicensekey> with the activation key for your specific Windows edition.
Here are the Windows 10 Volume License Keys:

Home: TX9XD-98N7V-6WMQ6-BX7FG-H8Q99

Home N: 3KHY7-WNT83-DGQKR-F7HPR-844BM

Home Single Language: 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH

Home Country Specific: PVMJN-6DFY6-9CCP6-7BKTT-D3WVR

Professional: W269N-WFGWX-YVC9B-4J6C9-T83GX

Professional N: MH37W-N47XK-V7XM9-C7227-GCQG9

Education: NW6C2-QMPVW-D7KKK-3GKT6-VCFB2

Education N: 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ

Enterprise: NPPR9-FWDCX-D2C8J-H872K-2YT43

Enterprise N: DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4

Note: Press Enter after typing the command to execute it.

Step 2: Configure the KMS Server
Connect your device to the KMS server by running:

`slmgr /skms kms.msguides.com`

Step 3: Activate Windows
Activate your Windows installation with the command:

`slmgr /ato`


Error Handling:
If you encounter error 0xC004F074, it may indicate an unstable internet connection or a busy server. Ensure your device is online and retry the command until activation succeeds.

Step 4: Verify Activation
Once successful, check your activation status to confirm that Windows 10 is activated.
