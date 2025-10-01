# happycasts
ad-free podcast app with AI features in Rust

I want to practice Rust during [Hacktoberfest](https://hacktoberfest.com/) 2025, so will use this opportunity to do so. My choice :P 🦀

### Problem statement

I have been using Pocket Casts for years and it has been fine. Recently in 2025, they implemented banner ads, which means
I need to find a new app for my podcasts. I also disagree with what the owner of the parent company has been doing with
wordpress. 

Finally I would like to add these features:

- [] AI automated digest of podcasts of your choosing
- [] Ability to remove the notification badge if you're not interested in the latest episode
      - context: if you have the badges shown in pocket casts, they force you to mark the latest episode as "listened to",
        which in the UX is not too different from archiving. There should be a middle ground, like a way to toggle the new
        episode badge at will. I think the default UX should be that the user opens the podcast list to mark the toggle as
        off. Then if desired, the user can choose the put the badge back (similar to "mark as unread" in messaging apps).
     
Source code for refences:

- [pocket-casts-ios](https://github.com/Automattic/pocket-casts-ios)
- [pocket-casts-android]([https://github.com/Automattic/pocket-casts-ios](https://github.com/Automattic/pocket-casts-android))

There may be other sources that can be used for inspiration, even maybe some in Rust or C/C++ or similar. But that's what I'm starting with.
