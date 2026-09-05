# HHGoa_Task3_Face_Blockchain
# HH Goa 2026 Task 3: Face Search and Blockchain Verification

## Project Overview

This project detects a face from an uploaded image, generates a face representation, performs a genuine reverse-image search using Google Lens through SerpApi, and stores the discovered web result and its SHA-256 fingerprint in a simulated blockchain.

## Workflow

1. Upload a face image.
2. Detect the face using OpenCV.
3. Generate a numerical face representation.
4. Upload the image to SerpApi.
5. Search for matching web results using Google Lens.
6. Select a real matching result returned by the search API.
7. Generate a SHA-256 fingerprint of the discovered result.
8. Store the result and fingerprint in a blockchain-style structure.
9. Verify the blockchain.
10. Modify the stored data to demonstrate tampering detection.
11. Restore the original data and create a clean verified blockchain.

## Technologies Used

- Python
- Google Colab
- OpenCV
- SerpApi
- Google Lens
- SHA-256 hashing
- Simulated blockchain
- JSON

## Blockchain Verification

The blockchain stores:

- Discovered result title
- Source website
- Result URL
- SHA-256 fingerprint
- Previous block hash
- Current block hash

The blockchain verification returns:

```text
True
