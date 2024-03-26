# Vision-Walk-Human-Computer-Interaction

Vision-Walk-HCI

This repository contains the source code for the Vision Walk application.

Branch Pattern

** Create a new branch for each new feature or a sub-feature for easy debugging. **

feature/{feature-name}
Once tested and working as expected.
Create a PR from feature to main.
Vision Walk Image Captioning Server Setup

CD to your Directory
Run: python3 -m venv LLM
activate LLM venv by: source LLM/bin/activate
In that directory with LLM (venv) activated run: pip install transformers torch pillow flask
Once installed, run: python image_captioning.py. The application will run on localhost port 8090.
To expose this locally hosted server for testing on iOS, use ngrok.
Install ngrock from brew or there package.
Create an account and get your API key, (Instructions on the website).
ngrok http #portno of the localhosted application that you want to expose. This will generate a string of web address use that
Vision Walk iOS Setup

Install Xcode from App Store, It will ask you automatically to install the required SDK of iOS.
Clone this project.
CD to iOS and run Vision Walk.xcodeproj.
Make changes in the CameraVC.swift
Reachibility.swift is to check the internet connection.

Vision Walk

Vision Walk

Explore the docs »

View Demo . Report Bug . Request Feature

![Contributors](https://img.shields.io/github/contributors/Khyati-Bareja/Vision Walk HCI?color=dark-green) ![Issues](https://img.shields.io/github/issues/Khyati-Bareja/Vision Walk HCI) ![License](https://img.shields.io/github/license/Khyati-Bareja/Vision Walk HCI)

Table Of Contents

About the Project
Built With
Getting Started
Prerequisites
Installation
Usage
Roadmap
Contributing
Authors
Acknowledgements
About The Project

Screen Shot

Vision Walk Description

Three components of Vision Walk are:

Your time should be focused on creating something amazing. A project that solves a problem and helps others
You shouldn't be doing the same tasks over and over like creating a README from scratch
You should element DRY principles to the rest of your life 😄
A list of commonly used resources that I find helpful are listed in the acknowledgements.

Built With

The development of the application was made possible by following technologies

Swift
Python
Getting Started

This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple example steps.

Prerequisites

This is an example of how to list things you need to use the software and how to install them.

npm
npm install npm@latest -g
Installation

Get a free API Key at https://example.com

Clone the repo

git clone https://github.com/your_username_/Project-Name.git
Install NPM packages
npm install
Enter your API in config.js
const API_KEY = 'ENTER YOUR API';
Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

For more examples, please refer to the Documentation

Roadmap

See the [open issues](https://github.com/Khyati-Bareja/Vision Walk HCI/issues) for a list of proposed features (and known issues).

Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/Khyati-Bareja/Vision Walk HCI/issues/new) to discuss it, or directly create a pull request after you edit the README.md file with necessary changes.
Please make sure you check your spelling and grammar.
Create individual PR for each suggestion.
Please also read through the [Code Of Conduct](https://github.com/Khyati-Bareja/Vision Walk HCI/blob/main/CODE_OF_CONDUCT.md) before posting your first idea as well.
Creating A Pull Request

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request

Authors

Khyati Bareja - Software Engineering Student@Concordia - Khyati Bareja - **
