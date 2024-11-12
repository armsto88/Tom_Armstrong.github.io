---
title: "Glossy-Pi"
excerpt: |
  Real-time detection of the Glossy-Black Cockatoo. <br/><img src='/images/500x300.png'>
collection: portfolio
---


Glossy-black Cockatoo Call Recognizer with Real-time Notifications and Daily Sound Clip Synchronization.

The South-Eastern Glossy-black Cockatoo, listed as threatened under the EPBC Act, is the smallest of the black cockatoos and exhibits highly selective feeding habits. Due to habitat destruction and human activities, their population is in decline. Understanding key behaviors such as flight paths, feeding sites, and nesting hollows presents a crucial opportunity to both enhance conservation efforts and boost breeding success, while also protecting vital feed trees.

Currently, monitoring strategies in the Noosa and Sunshine Coast LGAs, conducted by Bushland Conservation and Management, involve bioacoustic recorders such as the AudioMoth. These recorders are strategically placed in known hotspots and programmed to capture audio during specific times—morning and evening. Data from the recorders is stored on SD cards, which are then collected and processed through an R-based classifier (using binary point matching), followed by human verification in Raven software.

While this method is effective, there is often a significant delay between an event and its detection. The frequency of SD card collection, combined with the time required for processing, means that it can take weeks or even months for critical information to reach the team. Given the voluntary nature of the work and the remote locations of the devices, this delay can result in missed opportunities during the short mating, incubation, and fledging periods of the cockatoos.

To address this, a real-time solution was developed, incorporating IoT technology, machine learning, and single-board computers. This system enables immediate event recognition, with real-time notifications and daily synchronization of sound clip files. By drastically reducing the delay between data collection and analysis, this innovative approach offers significant improvements in the monitoring and conservation of the Glossy-black Cockatoo.

Objectives 📝


   - Build a cost-effective device that classifies and records calls using the Birdnet software (Open source).
   - Synchronize recordings to the cloud daily ☁️.
   - Standalone operation in respect to both power ⚡ and internet connectivity 📶.
   - Waterproof and durable enclosure 💧.
   - Raspberry Pi system info, synced daily to a spreadsheet 📊 (CPU load, system temp., battery monitoring).
   - Low power shut down and restart when battery voltage is sufficient 🔋.

Benefits 🌟

Receiving Glossy detection data in real-time offers several benefits: it enables the collection of more data over larger areas with fewer human resources, leading to a better understanding of bird activity. This increased data helps in identifying nesting sites more effectively, allowing for targeted conservation measures. Additionally, the devices used are discreet and cost-effective, providing a low-impact and affordable monitoring solution that minimally affects Glossy-black behavior.

Design and Software 💻

The Glossy Pi system uses a Raspberry Pi 4B equipped with a 4G modem and dedicated charging hardware for the lithium-ion battery. It runs Birdnet-pi, an open-source software for analyzing and classifying bird calls. Classified calls are recorded as 15-second MP3 files and scheduled for daily transfer to a cloud-based, shareable folder.
This modular unit allows for flexibility in hardware and software updates, enabling ongoing improvements in efficiency. Currently, we use a pre-existing machine learning model from BirdNet for proof of concept. With additional funding, we plan to develop a custom machine learning algorithm to enhance classification accuracy and control over various call types, thus increasing the value of our data.

While we utilize BirdNet’s open-source software, all other aspects of the unit, including intellectual property, are owned by Bushland Conservation Management.

![Image 1](images/Glossy_pi_1.jpg) ![Image 2](images/Glossy_pi_2.jpg) 
![Image 1](images/Glossy_pi_3.jpg) ![Image 2](images/Glossy_pi_4.jpg) 

---

**In collaboration with**

