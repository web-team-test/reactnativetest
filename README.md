# React Native Test

## Objectives - Goals App:

### Create an app to Add and Remove goals:

1. Clicking the "Add New Goal" button should open a new Modal which contains a text input to enter a goal, "Add" and "Cancel" buttons.

2. Entering a goal within text input and clicking "Add" should add the goal to the list of goals and "Cancel" should close the modal and switch back to display the list of goals. If "Add" is clicked without entering any text an Alert or Error containing "Please enter Goal Text" should be dispalyed.

3. Clicking one of the goals within the list should delete/remove the specific goal from the list.

Scope: Mobile Devices (iOS and Android)

### Additional Considerations:

1. Duplicate goals can be added to the list (Hint: Use an Id or Key for each goal)
2. Either functional or class based components can be used for the implementation
3. The app can be built using Expo or React Native project templates

## Goals App Preview

![React Native Test](/test/GoalApp-Test.gif 'React Native Test')

## Prerequisites

#### Complete [Setting up the development environment](https://reactnative.dev/docs/environment-setup) with React Native CLI

#### node version >= 16

## Install

```sh
npm install
```

## Usage

```sh
npm start
```

## Open Simulators

### 1. iOS

```sh
npm run ios
```

### 2. Android

```sh
npm run android
```
