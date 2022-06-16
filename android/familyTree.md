# Family Tree
<a href="https://play.google.com/store/apps/details?id=com.artevak.familytree">![Version](https://img.shields.io/badge/-Playstore-333333?style=flat&logo=android)</a>

![Banner](https://user-images.githubusercontent.com/31025016/173978054-80ded9ce-b53e-4b8b-a97d-04d18eabcb31.png)

## Description
Family Tree is an android app that can describe how big your family is with easy-to-understand descriptions. You can also communicate through an application that will be connected to the whatsapp application.
It can display up to 5 offspring, your grandparent, your parent, you, your child, your grandchild and your brothers/sisters. You can organize it to keep up to date.

It was modified from <a href="https://github.com/ssj64260/FamilyTreeView">FamilyTreeView</a> repository. 

## What's change
### Online Capability
It allow user to no worry about losing family data when user change the devices.
### Authentication
This feature for security purpose and identify you as a valid user and showing your existing data (if available)
### Family Sharing
User can share their family data to other family member. So they can adding others members into chart

## Technologies
### Database
For database it uses Firebase Realtime Database to store family member datas
### Authentication
User who uses the app as a guest, will be identifying using Firebase Authentication who generate on the first time open app. User login will be identify their data on Firebase Realtime Database
### Image Upload
<a href="https://uploadcare.com/">Uploadcare</a> allow us to upload image and use it for free.
