# WebBench
Benchmark browser agents on ~2.5k READ &amp; ACTION based tasks

---

# 🌐 WebBench: The Ultimate Browser Agent Benchmark 🖥️

Browser agents are transforming the way we automate complex, real-world web tasks. But, evaluating them effectively? That's been tricky—until now.

**Introducing WebBench**, the first, real-world benchmark of action based tasks for browser-based web agents.

---

## 🚀 Why WebBench?

Existing benchmarks for browser agents either use offline simulations or are limited to simple read-only tasks. The web is dynamic, diverse, and unpredictable—your benchmarks should be too.

WebBench fills this crucial gap by providing:

* **Real-world complexity**: \~Realistic web-based read and action-oriented tasks.
* **Diverse coverage**: Spanning 450+ real websites, capturing the true variability of the modern web.
* **Open-source**: \~2,454 carefully curated tasks publicly released to drive innovation in browser automation.

---

## 🛠️ Built for Innovation

WebBench empowers researchers and developers to:

* **Accurately measure** real-world agent performance.
* **Rapidly prototype and validate** browser agents across diverse web scenarios.
* **Push the boundaries** of what's possible in browser-based automation.

---

## 📚 Dataset Highlights

| Category           | Description                                             | Example                                                                                                                                                                             | Count (% of dataset) |
| ------------------ | ------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| READ               | Tasks that require searching and extracting information | “Navigate to the news section and summarize the headline and key points from the latest science policy update.”                                                                     | 1580 (64.4%)         |
| CREATE             | Tasks that require creating data on the website         | “Log in to your account and create a new board titled "Summer 2024" in the "Wish List" section, then add a "sleeveless midi dress" from the Women’s category to it.”                | 512 (20.9%)          |
| UPDATE             | Tasks that require updating data on the website         | “Adjust your journal notification preferences in your Springer account to receive email updates about "Online First" articles instead of the default monthly summary.”              | 173 (7.1%)           |
| DELETE             | Tasks that require deleting data from the website       | “Log in to your account, create a temporary test question in the Academia community titled "Test Question for Deletion," then delete it and confirm its removal from your profile.” | 149 (6.1%)           |
| FILE\_MANIPULATION | Tasks that require downloading a file from the internet | “Locate a downloadable recipe printout for a popular dessert recipe, download the file, and verify that the filename includes the recipe’s name.”                                   | 40 (1.5%)            |

### 🌎 Website Categories

The 452 websites are distributed across 17 primary categories. We sampled benchmark websites from the top 1000 websites globally by web traffic. This dataset was cleaned by removing repeat domains, sites without English translations, or sites blocked by paywalls.

---

## 🤝 Join the Community

Contribute, benchmark, and collaborate:

* 🌟 Check out our [dataset card](https://huggingface.co/datasets/Halluminate/WebBench).
* 🚀 Check out our [technical report]([https://halluminate.ai/](https://halluminate.ai/blog/benchmark)).


more coming soon... 
