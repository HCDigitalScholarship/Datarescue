# Web Archiving Using Conifer

Web archiving is crucial for preserving digital information, ensuring access for future research, and documenting evolving web content. Most of us have experienced the frustration of trying to access online content that no longer exists or has changed significantly from what we remember.

There are many tools and methods for web archiving, each producing different formats of archived web content. The three main types of web archiving are:

- **Remote harvesting**: Uses web crawlers to browse and capture webpages.
- **Database harvesting**: Involves exporting data from a database into a standard schema such as XML.
- **Transactional harvesting**: Captures web pages based on user interactions (such as viewing a page).

For more information on these other types of web archiving and how to use web crawlers, see our [Web Archiving and Data Rescue Lib Guide](https://guides.tricolib.brynmawr.edu/c.php?g=1451861&p=107914) and [Virginia Tech University Libraries Web Archiving Lib Guide](https://guides.lib.vt.edu/webarchiving/home#:~:text=Types%20of%20Web%20Crawling,page%2C%20and%20trigger%20a%20capture).



Today, we’ll focus on the third method: **transactional harvesting**, using an open-source tool called **Conifer**. Conifer has a high success rate in capturing complex websites with elements like embedded videos and 3D graphics. Its user-friendly interface makes it approachable for those new to web archiving. Another advantage is that it can capture content visible only to logged-in users, which may differ from public views.

> **Note on privacy:** If you need to capture a site that requires login, consider creating a throwaway account just for web archiving. Your login credentials may be captured as part of your archived session.

Conifer provides **5GB of free storage**, and access to publicly shared collections is free and unlimited.

We’ll use the U.S. Environmental Protection Agency (EPA) website for this tutorial, but feel free to substitute any site of interest.

---

## Tutorial

### 1. Create a Conifer Account

- Navigate to [https://conifer.rhizome.org](https://conifer.rhizome.org) and click on the **“Sign Up”** button.
- Fill in the required information, including your email address and password.
- Confirm your account via email.

### 2. Log into Conifer

- Return to Conifer’s homepage and log in with your credentials.

### 3. Start a Web Archiving Session

- In the **“Capture Address”** field, enter the URL of the website you'd like to archive — for this tutorial, enter: `https://www.epa.gov/`.
- Select your preferred capture method:
  - Your local browser
  - A remote browser
  - The ArchiveWeb.page desktop app

  > For today’s exercise, we’ll use the **local browser** option. Depending on the website and its content, you might need to experiment with different methods.

- Begin navigating through the website. Conifer records pages and interactions in real-time.

#### Suggestions for exploring the EPA site:

- Navigate to different sections using the top menu.
- Perform a search using the search box and archive the results.
- Switch to another language using the footer menu and archive the translated content.
- Interact with multimedia elements such as videos or chat features.

---

### 4. Browser Methods for Web Archiving

Your choice of browser can affect how data is captured or displayed. Websites may render differently across browsers due to varying support for image formats, JavaScript, or plugins. You may need to test different capture methods — using your **local browser**, a **remote browser**, or the **ArchiveWeb.page desktop app** — depending on the site’s configuration.


For more details, see [Conifer’s *Choosing a Browser* documentation](https://guide.conifer.rhizome.org/docs/capture-approaches/capture-browsers/).



---

### 5. End the Web Capture Session

- When you've finished capturing the content, click the **“Stop”** button (red dot) in the top-left corner.
- Provide a **name** and **description** for your session to help identify it later.
- Organize your sessions into **collections** for easier access and management.

---

# Advocacy Resources


