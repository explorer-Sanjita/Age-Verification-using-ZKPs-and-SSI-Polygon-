PREREQUISITES: POLYGON ID APP MUST BE DOWNLOADED IN PROVER'S DEVICE AND IT MUST HAVE A VERIFIABLE CREDENTIAL ISSUED BY ISSUER

How to run the project?

1) npm install 
2) On VSCode Terminal npm run dev
3) On Mac terminal ngrok http 3000 (for localhost:3000)
4) Update the NEXT_PUBLIC_DEVELOPMENT_URL in the .env.local file with your ngrok "Forwarding" URL seen on Mac terminal
5) Scan the QR code from the Polygon ID app to kick off the verification process.
PROVER HAS TO PROVE HE/SHE IS BORN BEFORE 1 JAN 2023 WITHOUT SHOWING HIS ACTUAL CREDENTIAL. ZK PROOF IS AUTOMATICALLY CREATED

Before Verification : Status is "Not Verified"
<img width="1136" alt="Screenshot 2024-04-23 at 9 56 40 AM" src="https://github.com/explorer-Sanjita/Age-Verification-using-ZKPs-and-SSI-Polygon-/assets/99412932/e7ff1633-a2a8-4247-8425-0dfe6444412b">


For verification, one has to open Polygon ID App on their device having a valid verifiable credential & scan the QR Code below, after that prover will be asked to choose the required verifiable crendential issued by a issuer. A ZK-Proof of this verifiable credential will be generated & thus verification will be done. 
After successful verification, the status changes to "Verified" as shown in figure below:
<img width="1136" alt="Screenshot 2024-04-23 at 10 09 14 AM" src="https://github.com/explorer-Sanjita/Age-Verification-using-ZKPs-and-SSI-Polygon-/assets/99412932/b7393f58-800a-4fb7-a648-491f3e3c66da">

NOTE: This project works on polygon mumbai testnet, but it can also work on polygon mainnet.
