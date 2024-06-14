<br />
<div align="center">
  <h1 align="center">Streaming</h1>

</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#setup">Setup</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## About The Project

Spark structured Streaming

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

This projects demonstrates spark structured streaming over NYC Taxi data

### Prerequisites

These are list of things you need to use the software and how to install them.

* docker
* docker-compose

### Setup

1. Build docker image in `src` directory
   ```sh
   docker build -t pyspark-stream -f src/Dockerfile .
   ```

## Usage

Start all services using docker compose.

```sh
   docker compose up -d
```

## Roadmap

* [x] Working setup
* [x] Query 1
* [x] Query 2
* [x] Query 3
* [x] Query 4
* [x] Visualization

See the [open issues](https://github.com/bazen-teklehaymanot/bdp/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/SupercoolFeature`)
3. Commit your Changes (`git commit -m 'Add some super cool feature'`)
4. Push to the Branch (`git push origin feature/SupercoolFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
