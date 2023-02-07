<p align="center">
<img alt="ViewCount" src="https://views.whatilearened.today/views/github/youtubeviewerbot/Youtube-View-Bot.svg">
<img alt="OS" src="https://img.shields.io/badge/OS-Windows%20/%20Linux / Mac-success">
<a href="https://github.com/youtubeviewerbot/Youtube-View-Bot/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/youtubeviewerbot/Youtube-View-Bot/total?label=Downloads&color=success"></a>
<a href="https://github.com/youtubeviewerbot/Youtube-View-Bot/issues?q=is%3Aissue+is%3Aclosed"><img alt="Closed issues" src="https://img.shields.io/github/issues-closed/youtubeviewerbot/Youtube-View-Bot.svg"></a>
<a href="https://github.com/youtubeviewerbot/Youtube-View-Bot/issues?q=is%3Aissue+is%3Aopen"><img alt="Open issues" src="https://img.shields.io/github/issues/youtubeviewerbot/Youtube-View-Bot"></a>
</p>
<p align="center">
  <a href="https://github.com/youtubeviewerbot/Youtube-View-Bot/releases/latest"><img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/youtubeviewerbot/Youtube-View-Bot?color=success"></a>
  <a href="https://github.com/youtubeviewerbot/Youtube-View-Bot/releases/latest"><img alt="GitHub Release Date" src="https://img.shields.io/github/release-date/youtubeviewerbot/Youtube-View-Bot?color=success"></a>
</p>

    Yb  dP  dP"Yb  88   88 888888 88   88 88""Yb 888888
     YbdP  dP   Yb 88   88   88   88   88 88__dP 88__   
      8P   Yb   dP Y8   8P   88   Y8   8P 88""Yb 88""   
     dP     YbodP  `YbodP'   88   `YbodP' 88oodP 888888 

                         Yb    dP 88 888888 Yb        dP 888888 88""Yb 
                          Yb  dP  88 88__    Yb  db  dP  88__   88__dP 
                           YbdP   88 88""     YbdPYbdP   88""   88"Yb  
                            YP    88 888888    YP  YP    888888 88  Yb
                            
# Windows Download

[Download For Windows](https://github.com/youtubeviewerbot/YouTube-Viewer/releases/download/1.8.0/YouTube-Viewer_win_1.8.0.zip)

# YouTube Viewer
Simple program to increase YouTube views written in Python. Works with live stream too.

**Disclaimer:** This has been developed for educational purposes only. Any action you take using this script is strictly at your own risk. I will not be liable for any losses or damages you face using this script.

**Cons:** There will be some views drop always. 

# Support
   Consider a donation to keep this project alive and for the countless hours of work and testing :)
   
  **PayPal :** https://paypal.me/youtubeviewerbot
  
  **Bitcoin :** `bc1q5knwa6xgvrkgkgl8f9c5wyws4ddp58pe2r79kl`

# Topics
[Requirements](https://github.com/youtubeviewerbot/Youtube-View-Bot#requirements)  
[New Update](https://github.com/youtubeviewerbot/Youtube-View-Bot#new-update)  
[Features](https://github.com/youtubeviewerbot/Youtube-View-Bot#features)   
[Proxies](https://github.com/youtubeviewerbot/Youtube-View-Bot#proxies)    
&ensp;&emsp;[Free Proxy](https://github.com/youtubeviewerbot/Youtube-View-Bot#free-proxy)  
&ensp;&emsp;[Premium Proxy](https://github.com/youtubeviewerbot/Youtube-View-Bot#premium-proxy)  
&ensp;&emsp;[Rotating Proxy](https://github.com/youtubeviewerbot/Youtube-View-Bot#rotating-proxy)  
[HTTP API](https://github.com/youtubeviewerbot/Youtube-View-Bot#http-api)  
[Config.json](https://github.com/youtubeviewerbot/Youtube-View-Bot#configjson)  
[Urls](https://github.com/youtubeviewerbot/Youtube-View-Bot#urls)    
[Search](https://github.com/youtubeviewerbot/Youtube-View-Bot#search)    
[Live Stream](https://github.com/youtubeviewerbot/Youtube-View-Bot#live-stream)    
[YouTube Music](https://github.com/youtubeviewerbot/Youtube-View-Bot#youtube-music)    
[Fast VPS](https://github.com/youtubeviewerbot/Youtube-View-Bot#fast-vps-with-unlimited-traffic)         
[Windows](https://github.com/youtubeviewerbot/Youtube-View-Bot#windows)  
&ensp;&emsp;[Binary Release](https://github.com/youtubeviewerbot/Youtube-View-Bot#binary-release)  
&ensp;&emsp;[Installation](https://github.com/youtubeviewerbot/Youtube-View-Bot#installation)  
&ensp;&emsp;[Usage](https://github.com/youtubeviewerbot/Youtube-View-Bot#usage)  
[Linux / Mac](https://github.com/youtubeviewerbot/Youtube-View-Bot#linux--mac)  
&ensp;&emsp;[Installation](https://github.com/youtubeviewerbot/Youtube-View-Bot#installation-1)  
&ensp;&emsp;[Usage](https://github.com/youtubeviewerbot/Youtube-View-Bot#usage)  
[Best Practices](https://github.com/youtubeviewerbot/Youtube-View-Bot#usage-1)  
[Issues](https://github.com/youtubeviewerbot/Youtube-View-Bot#issues)  
[Credits](https://github.com/youtubeviewerbot/Youtube-View-Bot#credits)  



# Requirements
 * **Python 3.7.x-3.9.x**
 * High speed Internet Connection
 * Good proxy list (http, https, socks4, socks5)
 * Google Chrome installed on your OS (not Chromium)


# Features
 * YouTube default, live streaming and YouTube Music support
 * Multithreaded and Dynamic thread support
 * Auto download updated chrome driver whenever user's Google Chrome version is updated
 * Patch chrome driver on the start of every thread by undetected-chromedriver
 * Proxy support 
      * location : text file (must be on path) / proxy API (should work with most of the proxy providers)
      * type : http, https, socks4, socks5
      * format : `ip:port`, `user:pass@ip:port`, `ip:port:user:pass`
      * proxy refresh after a certain time specified by the user
      * rotating proxy support
 * chrome v80+ randomized user agent based on platform
 * canvas,audio,font,webgl fingerprint defender and IP leak prevent by webrtc control
 * geolocation, timezone, referer spoofing
 * can add extra extensions in the `extension/custom_extension/` folder
 * direct link or search *keyword* on YouTube then watch the video by matching exact video *title*
 * modify **urls.txt, search.txt and config.json** on the fly without restarting program
 * HTTP api on localhost and a database to store view count
 * config.json to save settings
 * bypass consent page and several other pop up 
 * save bandwidth by reducing video quality 
 * can set higher(100%) watch duration percentage to increase *Watch time*, change playback speed
 * #### Traffic Sources
   * YouTube Search
   * Suggested Videos
   * External (Google, Yahoo, DuckDuckGo, Bing, Twitter)
   * End Screens
   * Channel Pages
   * Direct or unknown

# How to get started
  1) First, install the script following any one of these   
      * [Windows without installing python](https://github.com/youtubeviewerbot/Youtube-View-Bot#binary-release)    
      * [Windows from source code](https://github.com/youtubeviewerbot/Youtube-View-Bot#installation)    
      * [Linux / Mac from source code](https://github.com/youtubeviewerbot/Youtube-View-Bot#linux--mac)
   2) Then put your video links in the [urls.txt](https://github.com/youtubeviewerbot/Youtube-View-Bot#urls) file
   3) To search your video on YouTube and then play it put the search keywords and video title in the [search.txt](https://github.com/youtubeviewerbot/Youtube-View-Bot#search) file
   4) Get your [proxy](https://github.com/youtubeviewerbot/Youtube-View-Bot#proxies) list
   5) Run the script and follow the instructions from there.


# Proxies
 *[IPRoyal](https://iproyal.com?r=18862) offers datacenter and residential proxies. The Royal Residential proxies have a large pool with addresses in over 160 countries all over the world, so they can generate a massive number of views. IPRoyal agreed to provide a huge discount for my script users, so the price will be as low as 3.60USD/GB! To get this incredible 10% discount for Royal Residential proxies, use the discount code: `youtubers10`*


* ## Free Proxy
   Try not to use free proxies. But if you have a paid subscription and you want to use authenticated IP feature, then you can use the free proxy category. Provide your text file path (where you saved the proxies) when the script asks for a proxy file name or a proxy API.
   N.B: Available for **http(s)/socks4/socks5**
   
* ## Premium Proxy
   Proxies with authentication can also be done. To do so put your proxies in this format `username:password@ipaddress:port`or `ipaddress:port:username:password` in a text file. Every single line will contain a single proxy. Provide your text file path when the script asks for a proxy file name or a proxy API.
   
   N.B: Only available for **http** type proxy.

* ## Rotating Proxy
   You can also use the rotating proxies service. You can either authenticate your IP on your proxy provider service and use `ipaddress:port` as Main Gateway. 
   N.B: Available for **http(s)/socks4/socks5**

   Or direct use username:password combo like this `username:password@ipaddress:port` or `ipaddress:port:username:password` as Main Gateway.

   N.B: Only available for **http** type proxy.
   You can use proxy API too.

# HTTP API
   Live logs fetched every 10 seconds and statistics in graphs are available on http://localhost:5000/ .Or [http://ip_of_your_pc:5000/](http://ip_of_your_pc:5000/) use this to access from another device under same network. A SQLite Database is being used  to store your generated views from this script. 
   Last 200 logs from scripts are fetched every 10 seconds to show on website and graph is updated every 5 minutes.

# Config.json
   No need to type everything everytime you run the script. A config file will be created automatically to save and use your preferences.
   You can modify it on the fly without restarting the program.
   
# Urls
  Put video links in the urls.txt. For multiple videos place urls in multple lines.
  1) To find video link in YouTube click share and copy.
  2) If you have any external link which will redirect to your youtube video you can use that too. Example : when you post a YouTube video link in **twitter** and you hit play on twitter, you will get a link like this `https://t.co/xxxxxxxxxx?amp=1`. This is helpful because YouTube will see that views are coming from External Source like twitter in this example.

# Search
  Program can search youtube with the keyword you want and find video with video title. To do this you need to know what keyword can find your video on youtube search engine. Also you need to provide **exact** video title. Put keyword and title like this format `keyword :::: video title` in **search.txt**. You can use same `video title` for multiple `keyword` too.

  *If you don't know any keyword just put your `video title :::: video title` in search.txt*

   
# Live Stream
   This script supports live streams too. Just use this script as you would for the already uploaded video. Script will automatically know if your video is live. Just bear in mind, you need a **high-end pc** for higher threads to get more viewers.
   Basically, script will check every 60 secs if youtube shows `x watching now` is present. If your live stream ends, script will check 5 times to be sure. In another word, after your live stream ends, script takes 5 minutes to close the driver.
   
   If you have never used this script before, use this first for an already uploaded video. This way, you will have a better understanding of how this script works. To do so, keep reading.

# YouTube Music
   Can generate views on YouTube Music too. In **urls.txt** put your music link like this `https://music.youtube.com/watch?v=xxxxx`. Script will automatically load YouTube Music when it sees link have `music.youtube.com`. **Search feature is not available for this.** So you need to empty the search.txt otherwise it will start searching videos in default YouTube.


# Fast VPS with Unlimited Traffic
  *[PetroSky](https://petrosky.io/youtubeviewerbot) is one of the various CloudHosting services with the fastest and most convenient cloud technology. Their servers are powered by the latest **AMD RYZEN/EPYC CPUs** with High-Performance **NVMe SSD Hard Drives** that will let your application run faster than ever. You can get 2 vCPU with 4 GB ECC RAM for as low as 11.99€/month which will work very well for YouTube-Viewer script for 2 threads. Visit [PetroSky](https://petrosky.io/youtubeviewerbot) to get the fastest VPS with unlimited traffic at the lowest price. Use this code `youtubeviewerbot25` to get **25% discount**  on your purchase*

# Windows
* ## Binary Release

  For windows you can download binary releases from **[Binary releases](https://github.com/youtubeviewerbot/Youtube-View-Bot/releases)**. Download this file named `YouTube-Viewer_win_x.x.x.zip`, unzip it and run the `youtube_viewer.exe`. Or you can install it from source. To do so keep reading. 
  
* ## Installation

  First, make sure you have installed git and Python version between 3.7.x to 3.9.x
  
  Open command prompt and type
  ```
  git clone https://github.com/youtubeviewerbot/Youtube-View-Bot.git --depth 10
  ```
  ```
  cd YouTube-Viewer
  ```
  ```
  python -m pip install --upgrade pip wheel
  ```
  ```
  pip install "setuptools<59"
  ```
  ```
  pip install -r requirements.txt
  ```

* ## Important
   * If you've got a large free proxies collection, you should run this command to filter Good proxies. Then use **GoodProxy.txt** for proxy in **youtube_viewer.py**
      ```
      python proxy_check.py
      ```

   * After closing program, if chromedrivers are still running. You may want to double click **killdrive.bat** to close all chrome instances.

   * *urls.txt* or *search.txt* can't be empty. Otherwise you will see errors. Use both for better results.

* ## Usage
   * Open command prompt in YouTube-Viewer folder and run
        ```
        python youtube_viewer.py
        ```
   * Rest is self explanatory.

# Linux / Mac
* ## Installation

  First, make sure you have installed git and Python version between 3.7.x to 3.9.x
  
  Open your favourite terminal and run
   ```
  git clone https://github.com/youtubeviewerbot/Youtube-View-Bot.git --depth 10
  ```
  ```
  cd YouTube-Viewer
  ```
  ```
  python3 -m pip install --upgrade pip wheel
  ```
  ```
  pip3 install "setuptools<59"
  ```
  ```
  pip3 install -r requirements.txt
  ```

* ## Important
   * If you've got a large free proxies collection, you should run this command to filter Good proxies. Then use **GoodProxy.txt** for proxy in **youtube_viewer.py**
        ```
        python3 proxy_check.py
        ```

   * After closing program, if chromedrivers are still running. Open your terminal and run 
      ```bash
      ps aux | awk '/chrome/ { print $2 } ' | xargs kill -9
      ```
   * *urls.txt* or *search.txt* can't be empty. Otherwise you will see errors. Use both for better results.

* ## Usage
   * Open command prompt in YouTube-Viewer folder and run
        ```
        python3 youtube_viewer.py
        ```
   * Rest is self explanatory.
 
 # Best Practices
  To get the most out of this script you should maintain these things.
  * Don't use HEADLESS mode. Because no IP leak prevention, fingerprint defending, etc. can be done in headless mode.
  * Youtube doesn't count views from the same IP after a certain time. Like, don't expect to get 100 views from 10 proxies. If you want more views, try to use a lot of premium proxies(free proxies are flagged by most websites). DO NOT use TOR proxies.
  * It seems Rotating proxy gives the best result. But the IP MUST NOT change on each request. Set the sticky session or TTL to 5 to 15 minutes.
  * Use both [urls.txt](https://github.com/youtubeviewerbot/Youtube-View-Bot#urls) and [search.txt](https://github.com/youtubeviewerbot/Youtube-View-Bot#search)
  * And use as many [urls](https://github.com/youtubeviewerbot/Youtube-View-Bot#urls) and [keyword::::title](https://github.com/youtubeviewerbot/Youtube-View-Bot#search) as you can. Don't use just one video.


# Credits
 I want to thank all of you who have opened an issue or shared your code snippets or ideas with me! 
