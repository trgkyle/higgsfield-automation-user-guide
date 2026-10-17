[![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://chromewebstore.google.com/detail/higgsfield-automation-aut/nfokangfiojilfhfelhhbmbdibdndndp)

# 🚀 Higgsfield Automation v1.0.1 - Higgsfield.ai AI Automation [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![中文](https://img.shields.io/badge/中文-red)](README_zh.md)

**Higgsfield Automation** is a productivity tool that automates your creative workflow on Higgsfield.ai. Stop manually entering prompts one by one—automate the process and generate videos and images at scale.

-----

## ✨ Key Features

* **🚀 Batch Processing:** Queue dozens or hundreds of prompts and let the extension handle submission and generation automatically.
* **🧩 Workflow (visual drag-and-drop editor):** Connect prompts, images and generators on a canvas — e.g. generate images, then turn those images into videos automatically. Save several workflows, run one node or all of them, import/export them as files.
* **🎬 Text-to-Video Automation:** Generate videos from text descriptions. Supports batch processing with custom delays.
* **🎬 Frame-to-Video:** Use a start frame (or a start and end frame) and prompts to create dynamic videos.
* **🎬 Ingredients-to-Video:** Combine your uploaded images (characters, objects, scenes) with prompts to build videos.
* **🖼️ Text-to-Image Batching:** Create images from text with aspect ratios 16:9, 9:16, 1:1, 2:3, 3:2, 4:3 and 3:4.
* **🖼️ Image-to-Image:** Generate image variations from source images and prompts.
* **⚡ Unlimited Mode:** Use Higgsfield's Unlimited mode when generating (if your Higgsfield plan has it).
* **⚙️ Professional Controls:**
    * **Range Run:** Run only a part of your list (for example, prompts 5 to 20).
    * **Smart Delays:** Set a random wait time (from–to seconds) between prompts to manage rate limits.
    * **Auto Retry:** Retry failed generations automatically (1–20 times).
    * **Auto Download:** Automatically download results when generation completes (video up to 4K).
* **🔗 Concat / Edit Chains:** Continue a video from the previous prompt, or edit the image made by the previous prompt.
* **👤 Auto-add Character Images:** Images are matched to prompts automatically by file name.
* **📄 Import Prompts:** Load prompts from `.txt`, `.xlsx`, or `.csv` files.
* **📊 Real-time Queue Monitoring:** Monitor progress with the prompt queue and status of each prompt in the Side Panel.
* **📂 Organized File Management:** Downloads are sorted into project-based folders.
* **🌐 Multi-language Support:** 20 languages, including English, Vietnamese, Chinese, Korean, Japanese, Spanish, Portuguese, Hindi, French and German.

-----

## 📥 Installation

### Method 1: Chrome Web Store (Recommended)
1. Visit the [Chrome Web Store](https://chromewebstore.google.com/detail/higgsfield-automation-aut/nfokangfiojilfhfelhhbmbdibdndndp) and click **Add to Chrome**.

---

## 📖 User Guide

### Getting Started

1. **Navigate to Higgsfield.ai**
   - Open [higgsfield.ai](https://higgsfield.ai) and log in to your Higgsfield account.
   - The extension works on Higgsfield.ai pages. On other pages, the Side Panel shows a **Navigate to Higgsfield.ai** button.

2. **Open the Extension**
   - Click the extension icon in the Chrome toolbar. Pin it for easier access!

3. **Check your plan**
   - The banner at the top shows your plan. The **Free plan** has a daily prompt limit (`used/limit prompts today`).
   - Click **Sign in** and enter your email to check your plan. This email does not need to match your Higgsfield.ai account.
   - Click **Upgrade to Max** to remove the daily limit. One Max plan covers all extensions from Trường Nguyễn.

4. **Configure Batch Settings**
   - In the **Control** tab, you can set:
     - **Concurrent Prompts:** How many prompts to run at the same time.
     - **Random Delay:** Random wait time (from–to, 0–300 seconds) before handling the next prompt.

5. **Select a Mode**
   - Choose from: **Text to Video**, **Frame to Video**, **Ingredients to Video**, **Text to Image**, or **Image to Image**.

6. **Or open the Workflow editor**
   - Click **Workflow** at the bottom of the Control tab to build multi-step flows visually (see [6. Workflow](#6-workflow-visual-drag-and-drop-editor)).

### 1. Text-to-Video Mode

1. Select **Text to Video** mode.
2. Enter prompts into the input box (separate each prompt with a **blank line**).
3. Alternatively, click the **Upload** icon to import prompts from a `.txt`, `.xlsx`, or `.csv` file. For spreadsheets, choose the sheet and column to import.
4. (Optional) In **Video Mode per Prompt**, set a prompt to **5s concat** to continue its video with the next prompt.
5. Set **Save to folder** and choose the prompt range (**Start** to **End**).
6. Click **Run** to start the batch.

**Example Prompt:**
```
A futuristic cyberpunk city with neon lights reflecting in the rain.
The camera glides through the narrow alleys.

A peaceful Japanese garden with cherry blossoms falling into a pond.
A slow zoom into the koi fish swimming below.
```

### 2. Frame-to-Video Mode

1. Select **Frame to Video** mode.
2. In **Image Processing Option**, choose:
   - **Use Start frame only for each prompt** — one image per prompt.
   - **Use Start frame and End frame for each prompt** — two images per prompt (the first is the start frame, the second the end frame).
3. Click to upload or drag & drop your frame images (PNG, JPG, GIF up to 10MB each).
4. Enter prompts (separate with blank lines). Images are assigned to prompts in order — use the sort menu (Custom Order, Name A→Z, Newest…) or drag images to change the order.
5. Click **Run**.

### 3. Ingredients-to-Video Mode

1. Select **Ingredients to Video** mode.
2. Upload your ingredient images (characters, objects, backgrounds).
3. Choose **Max Input Images per Prompt** (1–16).
4. Enter prompts (separate with blank lines).
5. (Optional) Turn on **Auto-add character images** so each prompt uses images whose file name appears in the prompt. Example: `Anna.png` is added to any prompt that contains "Anna". If one name is inside a longer one, the longer one wins: with `1.png` and `11.png`, "image 11" uses only `11.png`.
6. Click **Run**.

### 4. Text-to-Image Mode

1. Select **Text to Image** mode.
2. Enter detailed descriptions for your images.
3. Configure the desired **Aspect Ratio** in the Settings tab.
4. (Optional) In **Image Mode per Prompt**, choose **Edit Image** to make the next prompt edit the image created by this prompt.
5. Click **Run**.

### 5. Image-to-Image Mode

1. Select **Image to Image** mode.
2. Upload source images and choose **Max Input Images per Prompt**.
3. Enter prompts for image variations. You can also turn on **Auto-add character images**.
4. (Optional) In **Image Mode per Prompt**, choose **Edit Image** to make the next prompt edit the image created by this prompt.
5. Click **Run**.

### 6. Workflow (Visual Drag-and-Drop Editor)

Workflow is a visual drag-and-drop editor for flows with several steps — for example: generate a few images, then use those images to make videos, then continue each video with another prompt. It opens in its own window and runs on your open higgsfield.ai tab.

#### Open it

* Click **Workflow** in the Control tab (bottom row).
* Already typed prompts or uploaded images in the side panel? Hover **Workflow** and click **Convert to workflow**: your prompts, each prompt's mode and your images become nodes in the editor, ready to run.

#### The screen

| Area | What it holds |
| :--- | :--- |
| **Left** | **Nodes** (click or drag one onto the canvas) and **Your workflows** (all saved workflows) |
| **Top bar** | The canvas tools: Undo/Redo, **Auto arrange**, fit view, **Example**, clear. On the right: the **Details** button, **Shortcuts** and the higgsfield.ai tab status |
| **Canvas** | Your nodes. Top-left: **Run all** (and **Stop** while running) and **Enable background mode** |

The **Details** button shows what needs attention: **Issues (n)** in red/yellow when something blocks a run, **Running 3/8** while generating. Click it to open a panel with the issues (click one to jump to the node), live progress, the run plan and the settings it uses.

#### Nodes

| Node | What it does |
| :--- | :--- |
| **Enter prompt** | One or more prompts, separated by a **blank line** |
| **Upload image** | Your images (drop files on it). Hover an image: 🔍 to view it larger, ✕ to remove it, the grip in the corner to drag it to another position. The order (or the sort menu) decides which prompt gets which image |
| **Generate Image** | Text to Image, or Image to Image when images are connected. Options: **Image Mode per Prompt**, **Max Input Images per Prompt**, **Auto-add character images** |
| **Generate Video** | Text to Video, or with images connected **Frame to Video** / **Components to Video** (= Ingredients to Video). Options: **Video Mode per Prompt**, images per prompt (shared with the side panel settings), **Auto-add character images** (Components to Video) |

Generate nodes are named automatically from their first prompt (`image_…` / `video_…`). Each prompt row shows the images it will receive, so you can check before running. Their preview takes the **aspect ratio** from the settings (a 9:16 node is narrower and taller).

#### Connect nodes

Drag from the round handle on the right of a node and **drop it anywhere on the other node** — the right input is picked for you. Nodes that accept the connection light up while you drag.

| From | To | Meaning |
| :--- | :--- | :--- |
| Enter prompt | Generate Image / Generate Video | The prompts to generate |
| Upload image | Generate Image / Generate Video | Reference images, start/end frames or components |
| Generate Image | Generate Image / Generate Video | The **generated images** become that node's input (it runs after the images are ready) |
| Generate Video — **last frame** output | Generate Video | The next video **continues from the last frame** of this one |
| Generate Video — **last frame** output | Generate Image | The **last frame** of each video becomes an input image (it runs after the video is ready) |
| Generate Video — **video** output 🎬 | Generate Video | The **generated video becomes a component** of the next one (Components to Video; it runs after the video is ready) |

#### Run

* **Run all** (top-left, or `Ctrl/⌘ + Enter`) runs the whole workflow in the right order: nodes waiting for generated images start automatically once those images exist.
* If **Run all** is disabled, the top bar shows **Issues (n)**: click it to see what to fix.
* Each Generate node also has its own **Run** button to run only that node. It is disabled until the nodes it depends on have finished (hover to see why).
* **Stop** cancels what is still running.
* While running, the connections into the node that is generating light up and flow, so you can see where the workflow is.

> ⚠️ **Chrome pauses higgsfield.ai when its tab isn't visible** (for example when the workflow window covers it full screen). Click **Enable background mode** (under **Run all** in the workflow, or in the side panel), then pick the higgsfield.ai tab in Chrome's dialog. This shares the higgsfield.ai tab (nothing is recorded or sent anywhere) so it keeps generating behind other windows. The green **Running in background** badge shows it's on; click ✕ to stop it.

#### Results

Results appear inside each Generate node. Hover a result: 🔍 opens it large, ✕ removes it (the eraser clears all results of the node). Videos play on hover. Files are still downloaded as usual.

The next node uses the **first result of each prompt**. To choose which one, drag a result by the grip in its top-left corner onto another result to swap them (images and videos).

#### Manage workflows

Under **Your workflows** (left): **New**, **Import**, and for each workflow the **⋯** menu — **Rename** (or double-click the name), **Duplicate**, **Export**, **Delete**. Everything is saved automatically.

* **Export** downloads a `.json` file. It starts with `//` comment lines that describe every node, property and connection, so you can give the file to an AI assistant and ask it to write new workflows. The comment lines are removed on import.
* **Import** a file with the button, or simply **drag the `.json` file onto the canvas**.

#### Editing shortcuts

Click **Shortcuts** in the top bar (or press `?`) to see them all.

| Action | Keys |
| :--- | :--- |
| Undo / Redo | `Ctrl/⌘ + Z` / `Ctrl/⌘ + Shift + Z` |
| Copy / Cut / Paste nodes (also into another workflow) | `Ctrl/⌘ + C / X / V` |
| Duplicate selection | `Ctrl/⌘ + D` |
| Select all / Add to selection / Box select | `Ctrl/⌘ + A` / `Ctrl/⌘ + click` / `Shift + drag` |
| Auto arrange | `Shift + A` |
| Delete selected | `Delete` |
| Run all / Run in background | `Ctrl/⌘ + Enter` / `Ctrl/⌘ + Shift + Enter` |

---

## ⚙️ Settings Configuration

Access the **Setting** tab to customize your experience:

* **Default Mode:** Set which mode opens by default.
* **Unlimited Mode:** **Enable** to use Higgsfield's Unlimited mode when generating, or **Disable** to generate normally.
* **Default Aspect Ratio:** Choose from 16:9 (YouTube), 9:16 (Shorts/Reels), 1:1 (Square), 2:3 (Portrait), 3:2 (Landscape), 4:3 (Classic), or 3:4 (Classic Portrait).
* **Default Video Option:** Default video mode for each prompt (5 seconds or 5 seconds concat).
* **Default Image Mode Option:** Default image mode for each prompt (New Image or Edit Image).
* **Max Retries on Failure:** How many times to retry a failed generation (1–20).
* **Auto Download Quality (Video):** 480p, 720p, 1080p, 2K, 4K, or **No Download**.
* **Auto Download Quality (Image):** 1k, or **No Download**.
* **Language:** Choose from 20 languages, including English, Tiếng Việt, 中文, 한국어, 日本語, Español, Português, Français and Deutsch.
* **Download Settings:** Files are saved to Chrome's Download folder, inside your project folder. Click ⚙️ to open Chrome's download settings.

Click **Save Settings** to apply, or **Reset Defaults** to restore the default values. Settings are synced across all browser tabs automatically.

---

## 💡 Tips & Best Practices

1. **Wait Times:** If you hit rate limits, increase **Random Delay** in the Control tab.
2. **Test First:** Run a small range (for example, prompts 1 to 2) before running the full list.
3. **Prompting:** Be specific. Detailed prompts lead to better results. Separate multiple prompts with a blank line. The extension adds the aspect ratio for you (`Create video with aspect ratio 16:9: …`), so you don't need to write it in each prompt.
4. **Character Images:** Name image files after your characters (e.g. `Anna.png`, `Tom.jpg`) to use **Auto-add character images**. When an image's name appears in the prompt, that image is placed at that spot in the prompt.
5. **File Organization:** Downloads are automatically sorted into project-based folders. Keep **Auto change file name** on so each file starts with its prompt number.
6. **Workflow:** Test one Generate node with its own **Run** button before **Run all**. Start from **Example** if you're new, and use **Export** to back up or share a workflow.

---

## 🔧 Troubleshooting

| Issue | Solution |
| :--- | :--- |
| **Extension not active** | Ensure you are on [higgsfield.ai](https://higgsfield.ai). Refresh the page if needed. |
| **"Please refresh Higgsfield.ai page" error** | Refresh the Higgsfield.ai page (Ctrl+R, F5) and try again. If the problem persists, reinstall the extension. |
| **Generation Errors** | Higgsfield.ai may be busy, or you may be out of Higgsfield credits. The extension will retry based on your **Max Retries** setting. |
| **Run button is disabled** | Add prompts, and for image modes upload enough images (one per prompt, or two per prompt with Start and End frame). |
| **Run button shows "Upgrade to Max"** | You have reached the daily free limit. Upgrade to Max or try again tomorrow. |
| **"Updating Extension" message** | A new version is installing. Wait a few seconds; if it takes too long, click **Reinstall from Chrome Web Store**. |
| **Downloads not working** | Ensure "Ask where to save each file before downloading" is **OFF** in Chrome Settings. |
| **Login Required** | Make sure you are logged into your Higgsfield.ai account. |
| **Workflow: generation stays at "Generating" forever** | Chrome paused the hidden higgsfield.ai tab. Turn on **Enable background mode** (or **Run in background**), or keep higgsfield.ai visible. |
| **Workflow: a node's Run button is disabled** | Hover it: run the node it depends on first, or fix the issue shown (e.g. no prompt connected). |
| **Workflow: Run all is disabled** | Click **Issues (n)** in the top bar to see what to fix; click an issue to jump to its node. |
| **Workflow: "No Higgsfield tab found"** | Open [higgsfield.ai](https://higgsfield.ai) in a tab (the green dot in the top bar shows it's connected). |

---

## 🔒 Privacy & Data

* **Local Processing:** All automation logic runs locally in your browser.
* **No Data Collection:** We do not store or collect your prompts, images, or account data.
* **Secure Storage:** Settings and workflows are saved only in your browser's local storage.
* **Background mode:** Sharing the higgsfield.ai tab only keeps it running. Nothing is recorded, saved or sent anywhere.

---

## 📞 Support

- **Author:** Trường Nguyễn
- **Website:** [kylenguyen.me](https://kylenguyen.me)
- **Feedback:** Use the "Report a bug to the author" link in the extension. Copy the logs from the **Debug Logs** tab and send them with your report.

---

## 📦 Version

Current version: **1.0.1**

---

## 📜 License

Copyright © 2026 **Trường Nguyễn**. All Rights Reserved.

This software is proprietary. Unauthorized copying or distribution is prohibited.

---

**Made with ❤️ by Trường Nguyễn**

---
