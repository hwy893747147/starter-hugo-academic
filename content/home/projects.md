---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Projects
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006



# 




# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: TODS
    company: Automated Time-series Outlier Detection System
    company_url: 'https://github.com/datamllab/tods'
    company_logo: tods
    location: 
    date_start: '2020-12-01'
    date_end: ''
    description: |2-
        * An end-to-end system that supports easy pipeline construction with more than 70 primitives for automated machine learning.
        * Top 3 contributor.
        * Mentor for new team members;
        * Explored neural architecture pipelining combination.
        * Open sourced on GitHub, with 450+ stars and 50+ forks.

  - title: Smart Homes
    company: Action and Emotion Detection Project
    company_url: 'https://drive.google.com/file/d/1CxZvbeXjmXK6T5B6KtJIW1Q4N7O42Y85/view?usp=sharing'
    company_logo: 
    location: 
    date_start: '2021-01-01'
    date_end: '2021-05-25'
    description: |2-
        * Deep learning project for action and emotion detection used in ”Smart Homes”.
        * Detected actions including coughing, hand washing, falling, cleaning windows, cleaning bathroom and washing feet.
        * Implemented with Keras, used Kinetics 700 dataset, built VGG16 and Xception CNNs for base model.
        * Found in total of 23000+ clips from 800+ YouTube videos, average accuracy 91.2%, ranked top three overall in the project competition.
        
  - title: MusicFace
    company: Automated Emotion Playlist Generator
    company_url: 'https://tx.ag/MusicFace'
    company_logo: 
    location: 
    date_start: '2019-08-01'
    date_end: '2019-12-25'
    description: |2-
        * Detection system to generate personal playlist based on age and mood.
        * Used Flickr & YouTube Music APIs.

  - title: GasDash
    company: Fuel Tracking Application
    company_url: 'https://play.google.com/store/apps/details?id=com.geotracking.gasdash'
    company_logo: 
    location: 
    date_start: '2020-01-01'
    date_end: '2020-12-25'
    description: |2-
        * Web, iOS and Andriod application for tracking & delivery of fuel trucks, deployed on Google Play Store.
        * Implemented using Google Maps API and OpenWeather API, programmed in Dart language.

design:
  columns: '2'
---
