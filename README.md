<h1 align="center">
  
  [Ominis-OSINT: Web Hunter](https://github.com/AnonCatalyst/Ominis-OSINT)
  
</h1>

<br>

<div align="center">

  <img src="src/img/video.gif" alt="Ominis Osint Project"/>
  
</div>

<br>
<br>
<br>

<div align="right">
  
### [**Wanna Help?**](https://cash.app/$anoncatalyst)
[`cash.app/$anoncatalyst`](https://cash.app/$anoncatalyst) : _**Wanna help prevent life from pausing development? DONATE!?**_

</div>

<hr>
<br>

<h3>
  
  [**Comming**](https://github.com/AnonCatalyst/Ominis-OSINT) `(paused)`

</h3>

- [ ] Refinement update.  Paused
- [ ] username search (`AliaStorm`) which is used at the end, is planned to receive a rebuild.
- [ ] new optional feature that introduces back `SerpApi`
- [ ] new optional feature to search the query also on the deep web from `DepthSearch`

<br>

<h3>

  [**Github Actions**](https://github.com/AnonCatalyst/Ominis-OSINT/edit/main/README.md#github-actions)
  
</h3>

>`Visit actions/workflows and chose any of the 3 options to try out Ominis OSINT right from github!`
- _Web Search_
  : [_`web-search.yml`_](https://github.com/AnonCatalyst/Ominis-OSINT/actions/workflows/web-search.yml)
  
- _Ominis Search_
  : [_`ominis-search.yml`_](https://github.com/AnonCatalyst/Ominis-OSINT/actions/workflows/ominis-search.yml)
  
- _Username Search_
  : [_`search-username.yml`_](https://github.com/AnonCatalyst/Ominis-OSINT/actions/workflows/search-username.yml)

<br>

<h3>
  
[**Information Obtained**](https://github.com/AnonCatalyst/Ominis-OSINT)

</h3>

   - `Discover online mentions of a query or username.`
   - `Identify potential social profiles and forums.`

<br>

<h3>
  
[**Support Server**](https://discord.gg/tgSacvyHqV) 

</h3>

`Help us grow our discord server or contact support by joining up with us today!` 
- [`Support Discord Server`](https://discord.gg/tgSacvyHqV)

<br>
<br>
<br>

| _ | Features | Description |
|---|----------|-------------|
| 1 | **`Google Search Filtering`** | _Take advantage of Google search by using the filtering features Country, Language, and date range_ |
| 2 | **`Enhanced User Interface`** | _Enjoy a redesigned interface for a seamless experience, suitable for both novice and experienced users_ |
| 3 | **`Expanded Digital Reconnaissance`** | _Conduct thorough investigations with advanced tools to gather and analyze publicly available information from diverse online sources_ |
| 4 | **`Threading Optimization`** | _Experience faster execution times with optimized threading, improving efficiency and reducing waiting periods during username searches_ |
| 5 | **`Detailed Results`** | _Gain comprehensive insights from search results, including detailed information extracted from various sources such as social profiles, mentions, and potential forum links_ |
| 6 | **`Proxy Validation`** | _The tool validates proxies for secure and efficient web requests, ensuring anonymity and privacy during the search process_ |
| 7 | **`Human-like Behavior Mimicking`** | _To mimic human-like behavior and avoid detection by anti-bot mechanisms, the tool randomizes user agents for each request_ |
| 8 | **`Randomized User Agents`** | _Utilizes randomized user agents for each request, further enhancing user anonymity through proxy rotation_ |
| 9 | **`Username Search`** | _Searches a list of URLs for a specific username with threading for parallel execution_ |

<br>

<h3>

  [Configuration](https://github.com/AnonCatalyst/Ominis-OSINT/edit/main/README.md#configuration)
  
</h3>

- Web search uses Google by default.
- Configure the list of URLs in `src/urls.txt` for username searches.

<br>

<h3>
  
  [Installation](https://github.com/AnonCatalyst/Ominis-OSINT/edit/main/README.md#installation)
  
</h3>

- **Optional PIP install:**

  - ```bash
    pip install Ominis-OSINT
    ```

- **From source**
  - ```bash
     git clone https://github.com/AnonCatalyst/Ominis-OSINT
     pip install -r requirements.txt
     ```
      - Run the following command at your own risk if your having installation issues when using pip 
        - ```bash
          pip install -r requirements.txt --break-system-packages
          ```

- Install using default install script
```bash
chmod +x install.sh
sudo sh install.sh
```

- **Install for windows**
```batch
Simply double-click the install.bat file or run it from Command Prompt.
```

<br>

<h3>

  [**Usage**](https://github.com/AnonCatalyst/Ominis-OSINT/edit/main/README.md#usage)
  
</h3>

1. Navigate to the script's directory:
   - `cd Ominis-OSINT`
2. Run on Windows:
   - Simply double-click the `ominis` __exe__ file or run it from Command Prompt.
4. Run the script normally:
   - `python3 ominis.py`

