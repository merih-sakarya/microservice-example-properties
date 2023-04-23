# Microservice Example Properties

This repository stores configuration properties for the "microservice-example" project. It contains YAML files used by the Spring Cloud Config Server to manage settings for each microservice.

## Structure

Each YAML file in this repository corresponds to a specific microservice or application profile in the "microservice-example" project. Currently, the files follow the pattern `service-name.yml`, where `service-name` represents the microservice's name. However, if you wish to create configurations for different profiles, you should follow the pattern `service-name-profile.yml`, where `profile` indicates the configuration profile.

## Usage

The Spring Cloud Config Server from the "microservice-example" project fetches the YAML files in this repository to provide centralized configuration management for all microservices in the system.

## Contributing

Please feel free to submit issues, fork the repository, and send pull requests to contribute to the project.

## License
This project is licensed under the terms of the MIT License.