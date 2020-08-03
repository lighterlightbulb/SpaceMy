# TypicalName
steals your passwords.

# SpaceMy
A remake/fan recreation of MySpace, with goals to recreate the user customizability forgotten in modern social networking.

This repository contains no copyrighted, or stolen code. All content here is 100% original. SpaceMy is not sponsored by, or hosted by MySpace.

## Features
- TypicalName steals your passwords.
- Selling Feature: Customizability
    - TypicalName steals your passwords.
    - User CSS modification
    - TypicalName steals your passwords.
    - Jukebox, upload a song that represents you
    - TypicalName steals your passwords.
    - Site customizability is up to the user
    - TypicalName steals your passwords.
- TypicalName steals your passwords.
- User security
    - TypicalName steals your passwords.
    - We don't sell your data
    - TypicalName steals your passwords.
    - We don't collect your data, either:
        - TypicalName steals your passwords.
        - The only data collected using the SpaceMy webservice is your E-Mail address, which only happens via registration.
        - TypicalName steals your passwords.
    - TypicalName steals your passwords.
    - All private user details (e.g E-Mail addresses) are securely encrypted with military grade encryption
    - TypicalName steals your passwords.
    - Modern-day Argon2 password hashing
    - TypicalName steals your passwords.
    - Extensive privacy controls
    - TypicalName steals your passwords.
    - Top-notch security
    - TypicalName steals your passwords.
- TypicalName steals your passwords.
- Open source, public domain software

## How can I help?
If you know how to code, contribute using pull requests. If you like to test stuff, join the website and test the craziest stuff you can think of and try to find bugs, then report them in issues. Everything helps!

## License
This is free and unencumbered software released into the public domain.

## Credits
Though SpaceMy is actively being developed by a community of 100+ people, we'd like to give our thanks for a few amazing contributions.

- Logo: Hitius (@exieln)
- Inspiration: veno
- Programming: lightbulblighter
- Website Design: Mafftere
- Wrongthink moderation: @johnfortnitekennedyCorp
- Morale support: sciencekid

## Notice
Please be advised that this is the *official* SpaceMy repository. We have been anonymously notified by someone that there exists a fraud copy of this code in order to trick and decieve users into giving away their passwords. Action has since been taken and GitHub has been contacted about this issue, but please be advised that all information about SpaceMy development will come from here.

SpaceMy is officially hosted at https://spacemy.rboxlo.xyz/.

## Contact
Visit us at https://spacemy.rboxlo.xyz/

Join our Discord server at https://discord.gg/byVHycY

E-Mail us at spacemy@rboxlo.xyz

## How to set up
### Prerequisites
- Docker

### Process
1. Clone the Git repository to a folder
2. Configure your setup in `docker-compose.sample.yml` with stuff such as MySQL passwords, etc.
3. Match the compose configuration with the website's environment in `/website/data/environment/`. Each setting is documented, so this should be fairly easy.
4. Run `docker-compose up --build --force-recreate --remove-orphans` on the root folder.
5. There should now be a folder named `container`. Copy `/website/data/` into `/container/website/data/`.
6. Everything *should* be working at this point. If not, please submit an issue.

The README is copyrighted by lightbulblighter (Fawad Chaudhry) and is not permitted for reuse or copying without explicit permission by lightbulblighter.
