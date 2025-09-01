+++
title = "CAMEO"
description = "Workshop: Pilot Task on Composed Access to Multimodal E-commerce Objects"
weight = 5
template="plain.html"
date = "2025-07-29"
+++

# CAMEO: Composed Access to Multimodal E-commerce Objects

This is a pilot task on Composed Access to Multimodal E-commerce Objects (CAMEO) at the NTCIR-19 Conference, focusing on enhancing e-commerce search and question answering through innovative multimodal approaches.

<video width="720" height="480" controls>
  <source src="/images/CAMEO.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

### Dataset Exploration Tool

[Explore the ViEcom-Rec dataset](https://mysceal.computing.dcu.ie/cameo/).
This tool allows you to interactively explore the dataset, view product details, reviews, and other relevant information to better understand the data you'll be working with.

### Overview

CAMEO presents two exciting subtasks, each designed to test your innovative solutions:

#### 1. Composed Image Retrieval (CIR)

Gone are the days of simple image search! In CIR, users provide a reference product *and* a textual modification to find a altered variant. Think of it as empowering users to describe exactly what they want, beyond just what they see.

* **Your Mission:** Given a product ID and a textual modification (e.g., "same type, but a larger size"), your system must return a ranked list of products that precisely match the revised intent.
* **Example Query:** "I want the same product, but made in Vietnam"
* **Evaluation:** Your performance will be measured using industry-standard metrics like Precision, Recall, and mean Average Precision (mAP) at K.

#### 2. Review-Based Question Answering (QA)

Online reviews are a treasure trove of information, but extracting specific answers can be a challenge. This subtask focuses on helping users get direct answers to their product questions from customer reviews.

* **Your Mission:** Given a product ID or image and a user question (e.g., "Is this suitable for dry skin?"), your system needs to provide a two-part answer:
    1.  A concise natural language answer (e.g., "Yes, it is suitable for dry skin.").
    2.  A list of supporting evidence sentences extracted from one or more product reviews.
* **The Unique Twist:** Unlike many existing datasets, CAMEO encourages you to aggregate evidence across *multiple* user reviews, reflecting how real consumers form opinions from diverse feedback!
* **Evaluation:** Your short answer will be evaluated using Exact Match (EM) and F1 score, while your evidence list will be assessed using sentence-level precision, recall, and F1.

### The ViEcom-Rec Dataset
Both subtasks are powered by the [ViEcom-Rec dataset](https://github.com/linh222/face_cleanser_recommendation_dataset), a robust collection of real-world e-commerce data from a Vietnamese platform.

* **Dataset Scale:** Over 369,000 Vietnamese-language product reviews from 304,708 users for 2,244 distinct products.
* **Rich Product Information:** Includes product images, reviews, seller info, product descriptions, and nine key attributes extracted by GPT-family models (item name, ingredient, product feature, skin type, capacity, design, brand, expiry, and origin).
* **Expanding Diversity:** While initially focused on face cleansers, we are expanding the dataset to include a wider range of cosmetics categories like sun cream, lipsticks, and face washers to better match real-world scenarios!
* **Open Access:** The ViEcom-Rec dataset is publicly available under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 license for non-commercial academic use at Github.
* **Bridging the Language Gap:** To ensure maximum participation, all Vietnamese text data will be accompanied by high-quality English translations, and task guidelines, evaluation scripts, and starter code will be provided in English
