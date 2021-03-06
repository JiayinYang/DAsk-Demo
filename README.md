# DAsk-Demo

This repository contains the demonstration video for our paper DAsk: Human-in-the-loop Information Extraction and Question-Answering System for the Electricity Domain at ISWC 2022 Demo Track. In the video, we go through three steps that are introduced in the paper: Knowledge Processing, Knowledge Application and Interactive Search. Since the product only has the Chinese-Version, we also give an English explanation in the video.
![workflow_final](https://user-images.githubusercontent.com/22947142/178135683-cb6a2e0b-9dc5-4046-abdd-0e2c30d56848.jpeg)



# Knowledge Processing

Paragraphs and question-answer pairs can be generated automatically. Users can use the human-in-loop annotation to improve the system accuracy. For demonstration, we use section 1-3 of the published standard "Q/GDW 10225-2018 Code for construction and acceptance of ±800kV overhead transmission line."[1] as an example.

## Paragraph Generation
<img width="1154" alt="Screen Shot 2022-07-10 at 4 01 51 PM" src="https://user-images.githubusercontent.com/22947142/178137699-8bf4c1f9-696f-4f1a-961b-f7edbddb26b1.png">


## QA Generation
<img width="1135" alt="Screen Shot 2022-07-10 at 4 02 24 PM" src="https://user-images.githubusercontent.com/22947142/178137703-8e7d63ac-629f-49ac-b993-4dd072aef578.png">

# Knowledge Application
Users can use the human-in-loop design to define tags and dictionaries. The tag defined can be used as an auxiliary information of interactive search. Dictionaries can be used to tune the word segmentation and term weights. Both annotations can help to improve the system accuracy.

## Defining Tags

<img width="1162" alt="Screen Shot 2022-07-10 at 4 48 43 PM" src="https://user-images.githubusercontent.com/22947142/178137999-a4f05d08-2237-4e62-b223-d847e21e86c9.png">

## Defining the Dictionary
<img width="1187" alt="Screen Shot 2022-07-10 at 4 49 02 PM" src="https://user-images.githubusercontent.com/22947142/178138006-1cb8f0d3-c4ee-41cb-bb6f-e7e1c47a1e1e.png">

# Interactive Search
As for the query "What is the allowable deviation of pit depth for tower", the system will recommend the query "What is the allowable deviation of pit depth for tower in the construction of 800kv Overhead Transmission Line". Here "800kv" and "Overhead Transmission Line" are two tags. The system recommends two tags during the user-input-query and comes out with more precise answers with the user's expectation. 

# Search Engine
<img width="1246" alt="Screen Shot 2022-07-10 at 4 03 07 PM" src="https://user-images.githubusercontent.com/22947142/178137712-6e7abfe9-4f48-4519-9358-f4679459b27e.png">
<img width="1246" alt="Screen Shot 2022-07-10 at 4 02 57 PM" src="https://user-images.githubusercontent.com/22947142/178137715-e7d4b32a-f66f-4f66-a402-fe8caed2944a.png">

# Citation
[1] Q/GDW 10225-2018 Code for construction and acceptance of ±800kV overhead transmission line. BZW86.com. (2020, January 12). Retrieved July 9, 2022, from https://www.bzw86.com/202959.html 




