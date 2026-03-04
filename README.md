# App freezes when adding multiple tables in NLHE game

## Bug ID
NG-POKER-NLHE-001

## Title
[NG][Redmi Note 11s][Poker][FN] App freezes when adding multiple tables in NLHE game

## Type
Functional

## Severity
Medium

## Frequency
Every Time

## Build Version
2.5.15

## Environment
- Device: Xiaomi Redmi Note 11s
- OS: Android 13
- Network: Wi-Fi
- App Type: Native Android Application

## Preconditions
- User is logged in
- Stable internet connection
- User is on the Poker lobby screen

## Steps to Reproduce
1. Open the NEXA Poker app  
2. Navigate to Poker from the main lobby  
3. Tap on **NLHE**  
4. Select a **$0.02 / $0.05 / $0.10** table  
5. Tap the **“+”** icon to add another table  

## Expected Result
The app should remain responsive while loading additional tables. New tables should load smoothly without affecting ongoing gameplay.

## Actual Result
The app becomes unresponsive after tapping the “+” icon. The loading indicator freezes for approximately 15 seconds, user interactions are ignored, and noticeable lag occurs before the table loads.

## Reproduction Rate
3 / 3 times

## Date & Time
- Date: 2026-02-25
- Time: 1:03 PM

## Evidence
Screenshots available in the `/screenshots` folder.



https://github.com/user-attachments/assets/0ae2ee07-6adf-4c18-9a92-86960bb73885
