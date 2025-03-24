# Currency Conversion Microservice

## Overview

### This microservice provides currency conversion functionality by fetching exchange rates from another service (currency-exchange).
### It supports both RestTemplate and Feign clients to communicate with the currency-exchange service.

## Features

    -> Converts currency based on the exchange rate provided by the currency-exchange service.

    -> Supports two approaches:

    -> RestTemplate for manual HTTP calls.

    -> Feign Client for declarative API calls.

    -> Retrieves conversion rates dynamically and calculates the total amount.