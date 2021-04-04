---
layout: page
title: Fetal Distress Classification
description: An LSTM classifier to predict fetal distress based on fetal heart rate and uterine contraction time series data.
duration: Jan 2019 - March 2019
importance: 2
selected: true
---

 Fetal distress before and during childbirth indicates that the fetus has been receiving inadequate oxygen. The goal was to develop a system that classifies a fetus as "distressed" or "normal" using fetal heart rate (FHR) and uterine contraction (UC) time series obtained from cardiotocography. We used the [CTU-CHB Intrapartum Cardiotocography Database](https://physionet.org/physiobank/database/ctu-uhb-ctgdb/){:target="\blank"} which consists of 552 readings sampled at 4 Hz. We extracted prominent features such as accelerations and decelerations from the data, and developed an LSTM classifier. My team and I won the first place in our category at the 2019 [Smart India Hackathon](https://www.sih.gov.in/){:target="\blank"} for our application to predict fetal distress.