# Perceptron Model with Docker

This repository contains a simple Perceptron model implemented in Python and a Dockerfile to facilitate deploying the model on any machine.

## Introduction

The Perceptron is a basic machine learning algorithm for binary classifiers. This repository demonstrates how to build a Perceptron model using Python and scikit-learn, and how to deploy it using Docker.

## Prerequisites

- Docker installed on your machine.

## Installation

1. Clone the repository to your local machine:

    ```sh
    git clone https://github.com/Natspy/Model_Percepton_Docker.git
    cd Model_Percepton_Docker
    ```

2. Build the Docker image:

    ```sh
    docker build -t perceptron-model .
    ```

## Usage

1. Run the Docker container:

    ```sh
    docker run perceptron-model
    ```

2. The Perceptron model will be trained and evaluated, and the accuracy will be printed to the console.
