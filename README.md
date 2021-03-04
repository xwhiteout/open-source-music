# OSM: Open Source Music

Have you ever wanted to participate in a song of a weird genre? Experiment with a band no strings attached?

OSM is an open source project meant to breed creativity with a focus on community.

## How it works

### 🌊 Start fresh

In OSM you can start a song from scratch by simply copying the [song template](./templates/song/README.md), filling it with your own material and uploading it to [music](/music). We will only ask you to stick to the [collaboration rules](#collaboration-rules) so the repository can be maintained in order.

### 🤝 Collaborate

Browse through the existing songs repertoire in the [music](music) directory and have a go to any of them. To do so, yo will have to create a `feature/` branch and request a pull to the _song starter_, more information below.

### 💬 Start a conversation

Use the [issues](https://github.com/xwhiteout/open-source-music/issues) tab to request song ideas, features, or anything to add to the project.

## Collaboration Rules

You will need a basic understanding of git and markdown, we recommend you to check out [GitHub Guides](https://guides.github.com/), a series of comprehensive, short articles that will help you catch up with the basics.

- **Songs**
  - Songs must follow the [song template](./templates/song/README.md) structure and be uploaded to the [music](music) directory.
  - The README.md file acts as a presentation sheet were the song starter is credited and the vision of the song is developed.
  - The **Song Starter** is the first person to collaborate on a song.
  - Songs must be approved by the administrators in a [Pull Request](https://github.com/xwhiteout/open-source-music/pulls) before being merged to `main`.
  - Contributors must create [feature pull requests](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) before adding to existing songs, which can only be merged once the *song starter* and an administrator approves them.
  - Remixes and different takes on OSM songs are allowed following the same formula as any other song, no credits required. We advice to let the song starters know and crediting the original songs.
  - Songs featuring non open source materials won't be allowed in order to avoid any legal issues.

- **Requests**
  - Requests can be made through [issues](https://github.com/xwhiteout/open-source-music/issues).
  - Requests must follow the `feature template`, using the `feature` tag.
  - Issues can be closed or linked in PRs by the addition of the `Fixes` or `Addresses` tags, look at [this article](https://docs.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue) for more information.

- **Tracks**
  - Each track (MIDI and/or mp3 files) goes in an independent folder with a name that represents it. 
  - **Padding** is the introduction of silence in a track to help alignment to an existing song. Padding is welcomed, but not required.
  - We recommend adding a two digit enumeration such as `bass-01` in case multiple tracks fulfilling similar roles are added in the future.
  
- **Resources**
  - VSTs or plugins required to achieve timbre can be added to the [resources](resources/README.md) directory. Adding them is welcomed, but not required. We expect every contributor to add their own flare and tools to the equation. 
  - Links to them in the song's README file.

- **Albums**
  - Compilation albums are planned to be released according to community interaction under the OSM artist label on platforms such as YouTube, Bandcamp and Spotify with no monetary intentions. Should we reach a point were money becomes a concern, we, the administrators, give our word that we'll give notice and try to reach an agreement on how to proceed before moving forwards.
  - Anybody is free to do their own compilations and share them to whatever platform they want as long as (in good faith) they credit the original source.

## More information

Head to the [docs](docs/README.md) directory for more information on the repository.
