eugenecad.org
=============

The web site of the Eugene ecosystem at [eugenecad.org](https://eugenecad.org)

## Docker
Download and install Docker.

  + Linux: check your package manager / distribution instructions.
  + Mac: [Instructions](https://docs.docker.com/docker-for-mac/install/)
  + Windows: [Instructions](https://docs.docker.com/docker-for-windows/install/) (Windows 10) / [Instructions](https://docs.docker.com/toolbox/toolbox_install_windows/) (Windows 7/8)
  
Pull, Build and run the image:

    docker compose up --build
	
Navigate to <http://localhost:8080> to use.
### Docker Hub

  + Docker images are built and deployed automatically via Github Actions See `.github/workflows/deploy.yml`.
  + They are published via the [NonaSoftware Docker Hub](https://hub.docker.com/repository/docker/nonasoftware/).
## Tutorials

For more details on how to use Nona's supported software tools check out our [Youtube tutorials](https://www.youtube.com/watch?v=Xq2n-iSfmBE&list=PLJAqoPLx9EE3iKr35HgyxUIvHQcIJGK-7). These are still a work in progress, but we'll be updating them regularly.

## Mission, Values, and Roadmap

For more information about our plans for `Nona` you can read our [home page and DEI](https://nonasoftware.org), which includes more details on our vision for supporting an open-source ecosystem around synthetic biology.
You can see details of [Trello project roadmap here](https://trello.com/nonaresearchfoundation).

## Contributing

Contributions are encouraged! Please read our [contributing guide](./docs/CONTRIBUTING.md) to get started. Given that we're in an early stage, you may want to review our guides as well:

* [Bug reports](./docs/CONTRIBUTING.md#bugs)
* [Feature requests](./docs/CONTRIBUTING.md#features)
* [Pull requests](./docs/CONTRIBUTING.md#pull-requests)

## Code of Conduct

`Nona` has a [Code of Conduct](./docs/CODE_OF_CONDUCT.md) that should be honored by everyone who participates in the `Nona` community.

## Governance

You can learn more about how the `Nona Research Foundation` is organized and managed from our [governance model]() which outlines our roles, responsibilities, and decision making processes, which includes information about, and ways to join the volunteers who help maintain Nona supported software. You can start by taking a look at [Code of Conduct](./docs/CODE_OF_CONDUCT.md) and [contributing guide](./docs/CONTRIBUTING.md). Our CI/CD is automatic to deploy to Amazon's ECS upon merging a pull request into production You can also always ask questions in the [slack developers group](https://join.slack.com/t/nona-network/shared_invite/zt-1etjfumia-3w4JreBT1rw_fQcPLM7dDw).

## help

We're a community over in [Slack for help](https://join.slack.com/t/nona-network/shared_invite/zt-1etjfumia-3w4JreBT1rw_fQcPLM7dDw) and all help and support requests in an appropriate `parchmint-help` channel. We look forward to interacting with you there. 

Bug reports should be made on our [github issues](https://github.com/nonasoftware/parchmint/issues/new?template=bug_report.md) using
the bug report template. If you think something isn't working, don't hesitate to reach out - it is probably us and not you!

## LICENSING
Check our [BSD-3 License](./docs/LICENSE)

## institutional and funding partners

![Nona Research Foundation](https://nonasofware.org) 
Want to be included as a partner or sponsor? Reach out to donate@nonasoftware.org