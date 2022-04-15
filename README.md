<p align="center">
    <img src="./images/logo_transparent.png?raw=true" title="WTF" alt="WTF" width="560" height="560" />
</p>

<p align="left">
    <a href="https://goreportcard.com/report/github.com/wtfutil/wtf"><img alt="Go Report Card" src="https://goreportcard.com/badge/github.com/wtfutil/wtf"></a>
    <a href="https://twitter.com/wtfutil"><img alt="Twitter" src="https://img.shields.io/badge/follow-on%20twitter-blue.svg"></a>
    <a href="https://deepsource.io/gh/wtfutil/wtf/?ref=repository-badge}" target="_blank"><img alt="DeepSource" title="DeepSource" src="https://deepsource.io/gh/wtfutil/wtf.svg/?label=active+issues&show_trend=true&token=kSJAbELF2TA7rEHjK6RPUrj5"/></a>
</p>

WTF (aka 'wtfutil') is the personal information dashboard for your terminal, providing at-a-glance access to your very important but infrequently-needed stats and data.

Used by thousands of developers and tech people around the world, WTF is free and open-source. To support the continued use and development of WTF, please consider sponsoring WTF via [GitHub Sponsors](https://github.com/sponsors/senorprogrammer).

### Are you a contributor or sponsor?

Awesome! [See here](https://wtfutil.com/sponsors/exit_message/) for how you can change the exit message, the message WTF shows when quitting, to something special just for you.

## Sponsored by

<p>
	<a href="https://airbrake.io/?utm_medium=sponsor&utm_source=WTFutill&utm_content=airbrake-home-page&utm_campaign=2021-sponsorships" target=_blank>
		<img src="./images/sponsors/airbrake.png?raw=true" height="60" title="Airbrake" alt="Airbrake" />
	</a>
</p>

<hr />

<p></p>

* [Installation](#installation)
    * ~~[Installing via Homebrew](#installing-via-homebrew)~~
    * ~~[Installing via MacPorts](#installing-via-macports)~~
    * ~~[Installing a Binary](#installing-a-binary)~~
    * ~~[Installing from Source](#installing-from-source)~~
    * [Running via Docker](#running-via-docker)
* [Communication](#communication)
    * [Slack](#slack)
    * [Twitter](#twitter)
* [Documentation](#documentation)
* [Modules](#modules)
* [Getting Bugs Fixed or Features Added](#getting-bugs-fixed-or-features-added)
* [Contributing to the Source Code](#contributing-to-the-source-code)
    * [Adding Dependencies](#adding-dependencies)
* [Contributing to the Documentation](#contributing-to-the-documentation)
* [Contributors](#contributors)
* [Acknowledgements](#acknowledgments)

<p align="center">
<img src="./images/screenshot.jpg" title="screenshot" width="720" height="420" />
</p>

## Installation

Other installs can be found at [wtfutil's website](https://wtfutil.com/installation/)

## Running via Docker

You can run `wtf` inside a docker container:

```bash
# download or create the Dockerfile
curl -o Dockerfile https://raw.githubusercontent.com/wtfutil/wtf/master/Dockerfile

# build the docker container
docker build -t wtfutil .

# or for a particular tag or branch
docker build --build-arg=version=v0.25.0 -t wtfutil .

# run the container
docker run -it wtfutil

# run container with a local config file
docker run -it -v path/to/config.yml:/config/config.yml wtfutil --config=/config/config.yml
```

## Documentation

See [https://wtfutil.com](https://wtfutil.com) for the definitive
documentation. Here's some short-cuts:

* [Installation](https://wtfutil.com/quick_start/)
* [Configuration](https://wtfutil.com/configuration/files/)
* [Module Documentation](https://wtfutil.com/modules/)

## Modules

Modules are the chunks of functionality that make WTF useful. Modules are added and configured by including their configuration values in your `config.yml` file. The documentation for each module describes how to configure them.

Some interesting modules you might consider adding to get you started:

* [DigitalOcean](https://wtfutil.com/modules/digitalocean/)
* [GitHub](https://wtfutil.com/modules/github/)
* [Google Calendar](https://wtfutil.com/modules/google/gcal/)
* [HackerNews](https://wtfutil.com/modules/hackernews/)
* [Have I Been Pwned](https://wtfutil.com/modules/hibp/)
* [NewRelic](https://wtfutil.com/modules/newrelic/)
* [OpsGenie](https://wtfutil.com/modules/opsgenie/)
* [Security](https://wtfutil.com/modules/security/)
* [Transmission](https://wtfutil.com/modules/transmission/)
* [Trello](https://wtfutil.com/modules/trello/)

## Getting Bugs Fixed or Features Added

## Contributing to the Source Code

## Contributing to the Documentation

### Adding Dependencies

## Contributors

## Acknowledgments
