# GitPitch Presentation Template

This branch contains **Sunkist**, a GitPitch presentation template.

In fact within this branch you will find three variations of the
Sunkist template, each optimized for specific use-cases:

1. Sunkist Base Template
2. Sunkist CodeMax Template
3. Sunkist Speaker Template

The content in this branch is a great example of how you can deliver
multiple-presentations (with optional asset sharing) within a
single Git repo branch. See the GitPitch Wiki for [further details](https://github.com/gitpitch/gitpitch/wiki/Asset-Sharing).

Each template variation is discussed in the sections following Quick Start.

## Quick Start

The fastest way to get started with this template is to copy the
entire contents of this branch into your own local repository. Then
git-add, commit, and push the template files to a public or 
private repo on GitHub, GitLab, or Bitbucket.

> Warning, this branch has it's own `README.md` and numerous other files under the `assets`, `codemax`, `speaker`, and `src` directories. These may be files or directories that you are already using in your own repo.  If you are going to copy the entire contents of this branch into your repo, please check to ensure that you do not accidentally overwrite existing files.

## Sunkist Base Template

[![GitPitch](https://gitpitch.com/assets/badge.svg)](https://gitpitch.com/gitpitch/templates/sunkist)

The Base template is an excellent starting point for any 
presentation author. The template markdown found in
[PITCHME.md](PITCHME.md), and the template settings found
in [PITCHME.yaml](PITCHME.yaml), provide great examples of
numerous GitPitch features.

To use only the Base template you will need to copy the following
files and directories into your own Git repository:

```
.
├── PITCHME.md
├── PITCHME.yaml
├── assets
└── src
```

Once you have those files under source control inside your
Git repo you are ready to start customizing the markdown content,
settings, imagery, styles, etc.

## Sunkist CodeMax Template

[![GitPitch](https://gitpitch.com/assets/badge.svg)](https://gitpitch.com/gitpitch/templates/sunkist?p=codemax)

The CodeMax template makes a small number of changes to the
custom CSS of the Base template in order to maximize the space
used when rendering code on any slide. The updated custom CSS is found 
in the [assets/css/PITCHME.codemax.css](assets/css/PITCHME.codemax.css) file.

To use only the CodeMax template you will need to copy the following
files and directories into your own Git repository:


```
.
├── assets
├── codemax
│   ├── PITCHME.md
│   └── PITCHME.yaml
└── src
```

Once you have those files under source control inside your
Git repo you are ready to start customizing the markdown content,
settings, imagery, styles, etc.

Note, if you want the CodeMax template to become the 
default presentation for your repo, move `codemax/PITCHME.md`
and `codemax/PITCHME.yaml` to the root directory of your repo.

## Sunkist Speaker Template

[![GitPitch](https://gitpitch.com/assets/badge.svg)](https://gitpitch.com/gitpitch/templates/sunkist?p=speaker)

The Speaker template is identical to the Base template with
one addition, sample speaker notes have been added
to the template markdown found in [speaker/PITCHME.md](speaker/PITCHME.md).
Open the **raw** view of this markdown file to see how simple
it is to add speaker notes to any slide.

To use only the Speaker template you will need to copy the following
files and directories into your own Git repository:

```
.
├── PITCHME.yaml
├── assets
├── speaker
│   └── PITCHME.md
└── src
```

Once you have those files under source control inside your
Git repo you are ready to start customizing the markdown content,
settings, imagery, styles, etc.

Note, if you want the Speaker template to become the 
default presentation for your repo, move `speaker/PITCHME.md`
to the root directory of your repo.

