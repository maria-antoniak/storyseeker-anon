# 🔭StorySeeker

This repository contains data, a codebook, and other resources for the detection of storytelling in online communities.

paper link removed for anonymity

<br>

## Quick Start with Colab

You can view a demonstration of how to load our annotations, fetch the texts, load our fine-tuned model from Hugging Face, and run predictions. If you use the Colab link, you don't need to download anything or set up anything on your local machine; everything will run in your internet browser.

Colab: removed for anonymity

Github: [link](https://github.com/maria-antoniak/storyseeker/blob/main/storyseeker_demo.ipynb)

<br>

## 🔭StorySeeker Dataset

This dataset includes 502 texts annotated with story- and event-spans.

You can view the data annotations [here](https://github.com/maria-antoniak/storyseeker/blob/main/storyseeker_data.csv).

We sampled Reddit posts and comments from the [Webis-TLDR-17](https://huggingface.co/datasets/webis/tldr-17) dataset. You must "rehydrate" the data by linking to the original dataset using the `id` column in our CSV.

We assign each of the top 500 subreddits in the dataset to a thematic category. These 33 categories can be found [here](https://github.com/maria-antoniak/storyseeker/blob/main/subreddit_categories.csv).

<br>

## 🔭StorySeeker Codebook

Our definition of storytelling and our full codebook can be found [here](https://github.com/maria-antoniak/storyseeker/blob/main/codebook.md).

<br>

## 🔭StorySeeker Models

The document classification model is available at [removed for anonymity] and can be accessed via Hugging Face.

<br>



