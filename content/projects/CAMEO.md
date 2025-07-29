+++
title = "CAMEO"
description = "Pilot Task on Composed Access to Multimodal E-commerce Objects"
weight = 5
template="plain.html"
date = "2025-07-29"
+++

# CAMEO: Composed Access to Multimodal E-commerce Objects

This is a pilot task on Composed Access to Multimodal E-commerce Objects (CAMEO) at the NTCIR-19 Conference, focusing on enhancing e-commerce search and question answering through innovative multimodal approaches.

## Unlock the Future of E-commerce Search!

Are you ready to revolutionize how people find products online? CAMEO invites you to participate in a groundbreaking pilot task designed to push the boundaries of multimodal product search! As online shopping becomes more dynamic, traditional search methods just aren't cutting it. Imagine a world where users can find exactly what they're looking for, even when their query is as nuanced as "like this, but in red" or "Is this good for oily skin?". That's the future CAMEO is building, and we want you to be a part of it!

### Why Participate in CAMEO?

* **Tackle Real-World E-commerce Challenges:** Directly address the evolving needs of online shoppers who rely heavily on images, product reviews, and community Q&A.
* **Innovate with Multimodal Data:** Work with a unique dataset combining product images, metadata, and over 369,000 authentic customer reviews.
* **Explore Low-Resource Language Processing:** Contribute to language equity by working with Vietnamese data, complete with high-quality English translations to ensure accessibility for all participants.
* **Advance the Fields of Information Retrieval and QA:** Your contributions will directly impact cutting-edge research in composed image retrieval, question answering, and multimodal understanding.

### The Challenges Await You!

CAMEO presents two exciting subtasks, each designed to test your innovative solutions:

#### 1. Composed Image Retrieval (CIR)

Gone are the days of simple image search! In CIR, users provide a reference product image *and* a textual modification to find a visually altered variant. Think of it as empowering users to describe exactly what they want, beyond just what they see.

* **Your Mission:** Given a product image and a textual modification (e.g., "same type, but a larger size"), your system must return a ranked list of product images that precisely match the revised intent.
* **Example Query:** "I want the same product, but made in Vietnam"
* **Evaluation:** Your performance will be measured using industry-standard metrics like Precision, Recall, and mean Average Precision (mAP) at K.

#### 2. Review-Based Question Answering (QA)

Online reviews are a treasure trove of information, but extracting specific answers can be a challenge. This subtask focuses on helping users get direct answers to their product questions from customer reviews.

* **Your Mission:** Given a product ID or image and a user question (e.g., "Is this suitable for dry skin?"), your system needs to provide a two-part answer:
    1.  A concise natural language answer (e.g., "Yes, it is suitable for dry skin.").
    2.  A list of supporting evidence sentences extracted from one or more product reviews.
* **The Unique Twist:** Unlike many existing datasets, CAMEO encourages you to aggregate evidence across *multiple* user reviews, reflecting how real consumers form opinions from diverse feedback!
* **Evaluation:** Your short answer will be evaluated using Exact Match (EM) and F1 score, while your evidence list will be assessed using sentence-level precision, recall, and F1.

### The ViEcom-Rec Dataset: Your Rich Resource

Both subtasks are powered by the ViEcom-Rec dataset, a robust collection of real-world e-commerce data from a Vietnamese platform.

* **Dataset Scale:** Over 369,000 Vietnamese-language product reviews from 304,708 users for 2,244 distinct products.
* **Rich Product Information:** Includes product images, reviews, seller info, product descriptions, and nine key attributes extracted by GPT-family models (item name, ingredient, product feature, skin type, capacity, design, brand, expiry, and origin).
* **Expanding Diversity:** While initially focused on face cleansers, we are expanding the dataset to include a wider range of cosmetics categories like sun cream, lipsticks, and face washers to better match real-world scenarios!
* **Open Access:** The ViEcom-Rec dataset is publicly available under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 license for non-commercial academic use at Github.
* **Bridging the Language Gap:** To ensure maximum participation, all Vietnamese text data will be accompanied by high-quality English translations, and task guidelines, evaluation scripts, and starter code will be provided in English

### Key Dates for Your Calendar (2025-2026)

* **October 2025:** Dataset preparation and triplet annotation will be underway.
* **January 2026:** Get ready! Training data and baseline models will be released.
* **June - September 2026:** Submissions system goes LIVE!
* **September 2026:** Results and analysis.
* **October 2026:** Paper submissions are due.
* **December 2026:** Present your groundbreaking work at the Workshop at NTCIR-19 Conference!

### Be a Pioneer!

Join us in shaping the future of e-commerce intelligence. Your research and solutions will contribute to a more natural, multimodal, and accessible product information experience for users worldwide.
