

# WebBench: A real-world benchmark for Browser Agents

WebBench is an open, task-oriented benchmark that measures how well browser agents handle realistic web workflows.
It contains **2 ,454 tasks** spread across **452 live websites** selected from the global top-1000 by traffic.

Last updated: May 28, 2025

---

## Dataset Composition

| Category           | Description                                             | Example                                                                                                                                                                             | Count (% of dataset) |
| ------------------ | ------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| READ               | Tasks that require searching and extracting information | “Navigate to the news section and summarize the headline and key points from the latest science policy update.”                                                                     | 1580 (64.4%)         |
| CREATE             | Tasks that require creating data on the website         | “Log in to your account and create a new board titled "Summer 2024" in the "Wish List" section, then add a "sleeveless midi dress" from the Women’s category to it.”                | 512 (20.9%)          |
| UPDATE             | Tasks that require updating data on the website         | “Adjust your journal notification preferences in your Springer account to receive email updates about "Online First" articles instead of the default monthly summary.”              | 173 (7.1%)           |
| DELETE             | Tasks that require deleting data from the website       | “Log in to your account, create a temporary test question in the Academia community titled "Test Question for Deletion," then delete it and confirm its removal from your profile.” | 149 (6.1%)           |
| FILE\_MANIPULATION | Tasks that require downloading a file from the internet | “Locate a downloadable recipe printout for a popular dessert recipe, download the file, and verify that the filename includes the recipe’s name.”                                   | 40 (1.5%)            |
                                                                                                                                                                     |

---

## Use Cases

* **Benchmarking**: Compare agent architectures on identical real-world tasks.
* **Ablation & Debugging**: Isolate failure modes (DOM changes, pop-ups, authentication).
* **Rapid Prototyping**: Validate improvements on a broad, realistic workload before production.

---

## Access

* Check out our dataset card [here](https://huggingface.co/datasets/Halluminate/WebBench)
* [Technical report](https://halluminate.ai/blog/benchmark)

Contributions—new tasks, evaluation scripts, or bug reports—are welcome.

