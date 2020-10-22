# BiocChallenges

Challenges for the Bioconductor community.

# Adding a challenge

New challenges are welcome, and can be submitted as pull requests.

- Copy one of the existing files named `challenge_*.Rmd` to a new Rmd file with a name that starts with `challenge_`.
  This is key, so that it is picked up when building the page that lists all challenges.
- Edit the YAML header as needed.
  + `topic` should be a concise description of the challenge, in one sentence.
  + `difficulty` must be one of `novice`, `intermediate`, or `advanced`.
  + `leaders` must be one or more entries in the format `github_username: "Full Name"`
  + `tags` must be a list of valid tags listed in [tags.Rmd](tags.Rmd).
    New tags are welcome, and can be submitted as part of the same pull request.
  + `duration` must be a free-form string indicating the minimum amount of time recommended to tackle the challenge.
- Edit the `Notes` section.
  Free-form markdown is accepted, but concise bullet points are encouraged.
