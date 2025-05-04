
# [All Contributors](https://allcontributors.org/) Bot

### Step 1: Install the bot (can do it at the organization or repo level)

https://allcontributors.org/docs/en/bot/installation


### Step 2: Update the README.md file 

#### Step 2a: add badge to top of README.md
Note: update your org and repo names
Example repo: https://github.com/data-umbrella/event-transcripts

**Example 1**: blog - [data-umbrella.github.io](https://github.com/data-umbrella/data-umbrella.github.io/README.md)
```plaintext
![All Contributors](https://img.shields.io/github/all-contributors/data-umbrella/data-umbrella.github.io?color=ee8449&style=flat-square)
```
This is what it looks like rendered: 
![All Contributors](https://img.shields.io/github/all-contributors/data-umbrella/data-umbrella.github.io?color=ee8449&style=flat-square)

**Example 2**: [event-transcripts](https://github.com/data-umbrella/event-transcripts/README.md)
```plaintext
![All Contributors](https://img.shields.io/github/all-contributors/data-umbrella/event-transcripts?color=ee8449&style=flat-square)
```

This is what it looks like rendered: 
![All Contributors](https://img.shields.io/github/all-contributors/data-umbrella/event-transcripts?color=ee8449&style=flat-square)

#### Step 2b: add Contributors comment to README.md
```html
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
```

### Step 3: Add the `.all-contributorsrc` file at root of repo
add this file:  
.all-contributorsrc

add this info to the file (update repo name)
```json
{
  "projectName": "event-transcripts",
  "projectOwner": "data-umbrella"
}
```

More information on bot configuration and options: https://allcontributors.org/docs/en/bot/configuration


### Step 4: Add a contributor with the bot
There are various types of [Contributions](https://allcontributors.org/docs/en/emoji-key).

1. Open up an issue
Example of issues:  
- Add timestamps contributor, samvmdev: https://github.com/data-umbrella/event-transcripts/issues/282
- Add community member:  https://github.com/data-umbrella/event-transcripts/issues/244
- Add for organizing events: https://github.com/data-umbrella/data-umbrella.github.io/issues/123

2. Syntax:

```
all-contributors add @github_user_name contribution_type
```


```
@all-contributors add @coni2k promotion
```
```
@all-contributors add @sandyweng promotion
```
```
@all-contributors add @Cristinamulas eventOrganizing
```

