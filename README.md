# Windows-firewall
# 🔥 Firewall Configuration on Windows 
## 🛠️ Tool Used
- **Operating System**: Windows 11
- **Firewall Tool**: Windows Defender Firewall with Advanced Security
- **Test Tool**: Telnet Client (via Command Prompt)

## ⚙️ Configuration Steps

### 1. Open Firewall Settings

- Press `Win + R`, type `wf.msc`, and hit **Enter**
- This opens **Windows Defender Firewall with Advanced Security**

### 2. Create Rule to Block Port 23

- Go to **Inbound Rules** → click **New Rule**
- Select **Port**, choose **TCP**, and enter port **23**
- Select **Block the connection**
- Apply to **Domain, Private, Public**
- Name the rule **"Block Telnet Port 23"**
- Finish the wizard

### 3. Screenshots 
- **firewall-main-window.png**: Firewall settings UI
- **new-rule-block-port23.png**: Rule creation wizard
- **new-rule-allow-port22.png** : rule creation wizard
-**rule-inbound-list.png**: Rule listed in Inbound Rules
- **rule-outbound-list.png**: Rule listed in Outbound Rules
- **telnet-test.png**: Failed connection to port 23
- **rule-deleted.png**: Rule removed
