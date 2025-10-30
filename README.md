# Venmo Onboarding Content System

A structured example of how product content can be organized, named, and connected across design and engineering.

## Overview
This demo represents the onboarding flow for Venmo, built using JSON to define screen content, navigation, and reusable strings.

The goal: show how content design can scale with systems thinking — where every string, button, and message is a component, not static text.

## Structure
- **/json/screens.json** — defines each screen and its content elements  
- **/json/onboardingFlow.json** — maps the flow order and transitions between screens  
- **/json/strings.json** *(optional next step)* — would store the reusable text variables (like `buttons.createAccount`)

## Screens
1. Account Access  
2. Account Type  
3. Phone Verification  
4. Code Verification  
5. User Name  
6. Legal Terms

## How this works with Design
Each content key can connect directly to Figma Variables for a single source of truth.
Designers, writers, and engineers can all work from the same set of structured content.

## Created by
**Brittney Villa** — UX Content Designer / Systems Architecht 
[thinkloop.co](https://thinkloop.co)
