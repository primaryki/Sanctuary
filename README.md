# Milestone 1 - Sanctuary (Unit 7 - Activity 2)

## Table of Contents

1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)

## Overview

### Description

 The Sanctuary app is created with the purpose of reuniting lost pets and their owners. The app allows users to upload and view information about lost animals,including pictures and arera lost/discovered. The information is displayed in a searchable feed, and on proof of ownership, owners may contact the discoverer of the pet.

### App Evaluation
Mobile:
    The app intends to make use of Google's Maps API to show last seen locations of animals. Camera integration will also be used for uploading images used to identify pets as well as verifying documents indicating ownership of lost pets. 
    
    
Story:
    Sanctuary aims to connect worried pet owners and concerned citizens, uniting them around the cause of protecting innocent animal life. People in pet friendly neighborhoods and living spaces will apprecite the added sense of security and community fostered by sanctuary.
    
Market:
    Sanctuary should to be accessible and intuitive to anyone concerned about animals, neigbourhood safety, and the general goodwill of the planet.
    
Habit:
    It is anticipated that missing pet owners will repeatedly use the app until their pet is listed as found. People who posted missing pets are also expected to repeatedly use the app until the owner of the animal is verified. The average user is expected to return to the app multiple times.
    
Scope:
    The core functionality of the application allows users to add and view information about lost pets to and from a database. At its most basic form the application is easily implementable. Additional features, such as geographical tagging and camera integration are expected to increase complexity of app development

## Product Spec

### 1. User Features (Required and Optional)

**Required Features**

1. Users can create a create a new account. The profile should contain information such as name, contact details, and information pertaining to an animal(lost/found/seen).
2. User authentication to ensure that user data and lost pet listings are secure.
3.  Pet owners can upload details about their lost pet including pet’s name, photo of pet, description of the pet, date lost, area lost.
5. Pet owners/Pet discoverers can upload details about a pet  (lost/found/seen) such as photos of the pet, descriptions, specifying the date and area the pet was (lost/found/seen), and the info of animal local animal services involved(Animal shelters/rescues,ASPCA).
6. Users can scroll feed of missing pets.
    *  Users  search for pet based on parameters such as animal type, animal color, location found/lost,without.
    *  Users can view details screen with more information about pet. 
7. Pet owners can provide proof of ownership such as vet records, photos, or ownership documents.
8. User update post if pet had been found.
9. Privacy control – users can decide if their contact information is visible to everyone.

**Optional Features**

1. Pet discoverers are required to turn animal over to local animal rescue/shelter, and provide information of such
2.  Chat/messaging System – pet owners and discoverers can communicate within the app to share additional information and arrange meetings for pet return.
3. Users can be alerted about new pet listings that match their criteria.
4. Multi-language - Users can view posts in English, Spanish, Chinese or French (most popular US languages).
5. Reward system – implement a monetary reward system to encourage users to help find missing pets. Pet owners can choose the reward amount and pay using the app.
6. Users can leave reviews and ratings for successful or unsuccessful reunions. This helps identify reliable and helpful persons when dealing with lost pet situations.

### 2. Screen Archetypes

**1. Login Screen** - User can login(screen is also shown when they log out.)  
* phone number/ email
* password

**2. Registration Screen** - User can create a new account.
* username 
* phone number/ email 
* password

**3. Lost Animal Feed** -  User can see a chronological feed of lost animals, yet to be found, updated by owners of lost pets.
* photo of animal 
* pet's name 
* date lost
* location lost


**4. Found Animal Stream** - User can see a  chronological feed of animals found, updated by users who have found pets.
* photo of animal 
* Area found
* Animal service used
* pet's name (if animal has a name/tag or collar)

**5. Search Animal Screen** - users can search for lost pets to filter found and lost stream.
* what can be filtered
    * type of pet
    * color of pet
    * date lost/found
    * location lost/found

**6. Pet Information Upload Screen** - pet owners/discoverers can upload necessary details about lost/found pets to add to display in appropriate stream stream.


**7. Proof of Ownership Upload Screen** - This screen allows pet owners to upload proof of ownership documents such as text describing their lost pet, additional photos of pet, vet records. *Stretch Features: videos of pet and map for geotagging.)

**9.Proof Ownership Screen** - Pet discoverer can view proof of ownership by possible owners. They can also add additional information to help pet owner verify their missing(Pictures/Videos of animal, details for identifying animal, *Stretch feature: Map displaying approximate location of found animal??* )
  
**10. Profile Screen** - user can view and edit profile information including name, photo, contact details, additional details. Privacy controls can be edited here.

**11. Update Lost Pet Status Screen** - Pet owners can update the status of their lost pet to indicate if they have been found.(Can add details such as where and when found and by who)


**12. Detail Screen** - The user will see all the details of both the owner and the lost pet
* included details
    * user
        * name 
        * perferred way of contact
        * desired ownership proof for pet
    * pet
        * name/collar/tag
        * last seen location (address)
        * date lost
        * pictures of pet
        * pet type 
        * lost/Found Status
        * Animal rescue service/Shelter/Practice if applicable

### 3. Navigation

> [name=IsaiahB: I think these 3 should all be one screen. Like the user would be able to upload all the details of the pet including rather its found or lost. All that will show up in the Search Animal screen. Then after tapping in the Search Animal screen the user will be directed to the Detail screen for more in depth details of the pet.]
* Lost Pet Listing Screen
* Found Pet Listing Screen
* Discover Pet Listing Screen


**Tab Navigation (Tab to Screen)**
* Profile Screen
* Review/Ratings Screen
* Discover Pet Listing Screen
* Search Animal Screen

**Flow Navigation (Screen to Screen)**
* Login Screen
    * Register Screen
    * Search Animal Screen
* Registration Screen
    * Login Screen
    * Search Animal Screen
* Profile Screen
    * Update Lost Pet Status Screen
    * Proof of Ownership Upload Screen
    * Proof Verification Screen
    * Lost Pet Listing Screen
    * Found Pet Listing Screen
* Search Animal Screen
    * Detail Screen

## Wireframes

[Add picture of your hand sketched wireframes in this section]  <img src="https://i.imgur.com/bquxyRL.jpeg?1" width=600>

<br>
 <img src="https://i.imgur.com/LNZ8hQV.jpeg?2" width=600>
<br>
 <img src="https://i.imgur.com/Acky0CS.jpeg?1" width=600>
<br>


### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

<br>

# Milestone 2 - Build Sprint 1 (Unit 8)

## GitHub Project board

[Add screenshot of your Project Board with three milestones visible in
this section]
<img src="https://imgur.com/LNZ8hQV" width=600>

## Issue cards

- [Add screenshot of your Project Board with the issues that you've been working on for this unit's milestone] <img src="YOUR_WIREFRAME_IMAGE_URL" width=600>
- [Add screenshot of your Project Board with the issues that you're working on in the **NEXT sprint**. It should include issues for next unit with assigned owners.] <img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

## Issues worked on this sprint

- List the issues you completed this sprint
- [Add giphy that shows current build progress for Milestone 2. Note: We will be looking for progression of work between Milestone 2 and 3. Make sure your giphys are not duplicated and clearly show the change from Sprint 1 to 2.]

<br>

# Milestone 3 - Build Sprint 2 (Unit 9)

## GitHub Project board

[Add screenshot of your Project Board with the updated status of issues for Milestone 3. Note that these should include the updated issues you worked on for this sprint and not be a duplicate of Milestone 2 Project board.] <img src="" width=600>

## Completed user stories

- List the completed user stories from this unit
- List any pending user stories / any user stories you decided to cut
from the original requirements

[Add video/gif of your current application that shows build progress]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

## App Demo Video

- Embed the YouTube/Vimeo link of your Completed Demo Day prep video
