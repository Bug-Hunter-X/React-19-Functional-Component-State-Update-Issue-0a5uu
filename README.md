# React 19 Functional Component State Update Issue

This repository demonstrates a subtle bug related to state updates in functional components within React 19. The issue arises from an incorrect usage of the `useState` hook, leading to unexpected rendering behavior. 

## Bug Description
The provided code snippet showcases a functional component that utilizes the `useState` hook to manage a counter.  However, due to an incorrect update mechanism, the component does not render correctly after the button click.

## Solution
The solution involves ensuring proper usage of the `useState` hook's setter function.