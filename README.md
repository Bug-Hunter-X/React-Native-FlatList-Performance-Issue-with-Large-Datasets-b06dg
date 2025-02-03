# React Native FlatList Performance Issue with Large Datasets

This repository demonstrates a common performance issue encountered when using FlatList in React Native with large datasets. The app may become unresponsive or even crash when attempting to render a significant number of items.

## Problem

The provided `bug.js` file contains a basic implementation of FlatList fetching data from an API. When the fetched data becomes substantial, the app experiences performance degradation.

## Solution

The `bugSolution.js` file offers solutions such as pagination, virtualization, and optimization techniques to efficiently handle large datasets within FlatList.  Specific techniques may include using `windowSize` for improved performance or implementing a custom solution based on the specific use case.