# OSM: Open Source Music

Have you ever wanted to participate in a song of a weird genre? Experiment with a band no strings attached?

OSM is an open source project meant to breed creativity with a focus on community.

## How it works

### 🌊 Start fresh

In OSM you can start a song from scratch by simply copying the [song template](./templates/song/README.md), filling it with your own material and uploading it to [music](/music). We will only ask you to stick to the [collaboration rules](#collaboration-rules) so the repository can be kept in order.

### 🤝 Collaborate

Browse through the existing song repertoire in the [music](music) directory and have a go to any of them. To do so, yo will have to create a branch and request a pull to the _song starter_, more information below.

### 💬 Start a conversation

Use the [issues](https://github.com/xwhiteout/open-source-music/issues) tab to request song ideas, features, or anything to add to the project.

## Collaboration Rules

You will need a basic understanding of git and markdown, we recommend you to check out [GitHub Guides](https://guides.github.com/), a series of short articles that will help you catch up with the basics.

- **Songs**
  - Songs must follow the [song template](./templates/song/README.md) structure and be uploaded to the [music](music) directory.
  - The README.md file acts as a presentation sheet were the _song starter_ is credited and the vision of the song is developed.
  - Songs must be approved by an administrator in a [Pull Request (PR)](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) before being merged to `main`.
  - The **Song Starter** is the name attributed to the creator of the PR were a song was started.
  - Contributors must create PRs to add material to existing songs, which can only be merged once the *song starter* and an administrator approves them.
  - The mp3 located at the start in the root song directory is meant to be kept up to date.
  - Remixes and different takes on OSM songs are allowed following the same formula as any other song, no credits required.
  - Songs featuring non open source materials won't be allowed in order to avoid any legal issues.

- **Requests**
  - Requests can be made through [issues](https://github.com/xwhiteout/open-source-music/issues).
  - Requests must follow the `feature template`, using the `feature` tag.

- **Tracks**
  - Each track (MIDI and/or mp3 files) goes in an folder within the song's folder, and must be namedin a way that represents it. 
  - **Padding** is the introduction of silence in a track to help align it to an existing song. Padding is welcomed, but not required.
  
- **Resources**
  - VSTs or plugins required to achieve timbre can be added to the [resources](resources/README.md) directory. Adding them is welcomed, but not required.
  - Links to resources go in the song's README file.

- **Albums**
  - Anybody is free to do their own compilations and share them to whatever platform they want as long as credit is given the original source or artists.

**The administration reserves the right of banning contributors that fail to go abide the rules or are perceived to act in bad faith.**

## More information

Head to the [docs](docs/README.md) directory for more information on the repository.
