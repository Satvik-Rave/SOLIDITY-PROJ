Pre req-
Install ipfs desktop, add metamask extension on google and create acc.
1. open remix ide and upload solidity code there
2. compile it
3. open ipfs desktop and upload your pic and copy CID (hash value)
4. come to remix put hash of image and image description and deploy the contract
5. click requestaccess- copy doctor (requestor id) from metamask acc, put it in requestaccess
6. put requesterID and image hash to approve the doctor in approverequester
7. click create contract and transact which adds the requestor is list
8. we can check if a requestor is valid or not by using isApproved requestor by putting requestorId
9. we can remove requestor aces to image by removeaccess function by putting requestorID and image hash
10. we can also check authorization using requesterID and patientAddress (click patient button)
11. use imagesHashes, put requesterID then doctor gets the image hash, put hash in imgDesc you get description
12. doctor uses this link, append image hash and get the image http://localhost:8080/ipfs/