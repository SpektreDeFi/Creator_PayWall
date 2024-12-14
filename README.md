# Access Protocol Paywall Widget

This is a **simple, ready-to-use widget and script** for Access Protocol creators. Use the widget to display a **Connect Wallet button** on your site, and the script to lock content behind an ACS staking requirement.

---

## **How It Works**
1. **Widget**:
   - Add the `widget.html` file to any page where you want to display the **Connect Wallet button**.
   - Users can connect their wallets using the button.

2. **Script**:
   - Add the `script.html` to pages you want locked behind an ACS staking requirement.
   - The script ensures that only users with the required ACS tokens staked can access the content.

---

## **Setup Instructions**

### **Step 1: Add the Widget**
1. Copy the code from `widget.html`.
2. Paste it into the page where you want the **Connect Wallet button** to appear.

### **Step 2: Add the Script**
1. Copy the code from `script.html`.
2. Paste it into the page header (or inject it into the header if you’re using platforms like Squarespace/Wix).
3. Use this on any pages you want locked behind an ACS staking requirement.

---

## **Customizing the Widget and Script**
You’ll need to update some specific lines to customize the widget and script for your pool:

### **1. Widget (widget.html)**
- **Line 1135–1140**:
  - Replace `poolId` with your **Access Protocol Pool ID**.
  - Replace `poolName` with your **pool name**.

- **Line 1157–1168**:
  - Update the **locked assets amount** (ACS required to unlock content).
  - Replace placeholder messages like "Welcome aboard, Ghosty!" with your custom messages.
  - Update the URLs to redirect users to the correct content or pages on your site.

---

### **2. Script (script.html)**
- **Line 50–55**:
  - Replace `poolId` with your **Access Protocol Pool ID**.
  - Replace `poolName` with your **pool name**.

- **Line 73–89**:
  - Update the **locked assets amount** (ACS required to unlock content).
  - Replace placeholder messages like "Welcome aboard, Ghosty!" with your custom messages.
  - Update the URLs to redirect users to the correct content or pages on your site.

---

## **Example**
Here’s how a completed update might look:

- **Pool ID**: `J8TpW6cypxheFUYjWn4mxS6ExvBEMxyMiRvrf43Nhnvy`
- **Pool Name**: `MyCustomPool`
- **ACS Locked Amount**: `5000 ACS`

---

## **Support**
If you run into issues:
- Verify you’ve updated the correct lines as listed above.
- Ensure you’re using valid pool IDs, names, and ACS thresholds.
- Contact Access Protocol support for further assistance.

---

