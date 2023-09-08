<p align="center">
  <img src="./gsoc-logo.png" alt="gsoc-logo.png"/>
</p>

# Google Summer of Code 2023 with Learning Equality | Kolibri

## Contributor Info
* Name - K. G. Akila Induranga
* Universtiy - University of Moratuwa, Sri Lanka
* GitHub - https://github.com/Akila-I
* Social Profiles
  - [LinkedIn](https://www.linkedin.com/in/akila-i/)
  - [StackOverflow](https://stackoverflow.com/users/16899162/akila-gamage)

## Mentors Info

* [Marcella Maki](https://github.com/marcellamaki)
* [Radina Matic](https://github.com/radinamatic)

## Project Description

- Title: Adding a custom text color picker for Kolibri EPUB renderer
- Organization: [Learning Equality](https://learningequality.org/)
- App repository: [Kolibri](https://github.com/learningequality/kolibri)
- [Project Proposal](./gsoc-project-proposal.pdf)

## Summary

The objective of this project was to add a custom text color picker for the Kolibri EPUB renderer. The current EPUB renderer has a set of predefined themes with text and background colors. In this project, I introduced a feature to the EPUB renderer where users can create custom themes with the text color, background color, and links color of their preference. Following actions were made possible with the new feature:

- Adding a new theme by selecting preferred colors for the text, background, links, and giving it a preferred name
- Deleting a custom created theme
- Applying a custom created theme to the EPUB viewer
- Editing a custom created theme to change the colors and the name

## Contributions

I worked with the mentors from Kolibri team to implement the new feature, having weekly meetings to discuss the progress and the next steps. Also, after I implemented the MVP of the feature, I got suggestions to improve the user interface from Kolibri design team as well. Following PRs were made to the Kolibri repository as a part of the project:

### Pull Requests

- [10877: Create custom theme container for epub renderer [GSoC '23]](https://github.com/learningequality/kolibri/pull/10877) (Closed - Draft PR to discuss the implementation)
- [11041: Add customized themes feature into EPUB renderer](https://github.com/learningequality/kolibri/pull/11041) (Merged)
- [11156: Epub viewer settings side bar redesigned](https://github.com/learningequality/kolibri/pull/11156) (Merged)

## Learning Experience
This project was my first time contributing to an open-source project. I had a great learning experience throughout the project. The accessibility aspect was the main area to focus on throughout the project. This project improves the accessibility of the Kolibri EPUB viewer for the users by letting them select preferred colors according to their visual needs when reading EPUB documents.

I got my skills improved in the following:
  - Testing a UI for accessibility with a screen reader
  - Implementing focus management of the UI elements for keyboard navigation
  - Implementing aria-labels for the UI elements

## Future Work

- New design for the UI is only partially implemented. Since it was suggested as an extra step, it can be fully implemented in the future.
- Currently, the custom themes are stored in the local storage of the browser. It can be improved by storing the themes in the Kolibri database.
- Importing and exporting custom themes can be added as an extension of this feature as future work.

## Acknowledgements

I want to express my gratitude to **Google** for organizing the Google Summer of Code programme and giving me the opportunity to work with **Learning Equality**. I would like to thank my mentors @Marcella Maki and @Radina Matic for their guidance and support throughout the project. I would also like to thank the **Kolibri** team for their help and support offered on the Slack channel. Finally, I would like to thank **my family**, **friends**, and **University of Moratuwa** for their support and encouragement throughout the project.
