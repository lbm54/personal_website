---
layout: project
title: Simple Food Log
tagline: Privacy-first food tracking with photo journaling
image: /assets/img/projects/simple-food-log.png
tech:
  - Flutter
  - Drift SQL
  - Riverpod
  - PDF Generation
---

Simple Food Log is a privacy-first iOS mobile app that helps users track their daily food intake with photos and notes. Perfect for working with dietitians, managing dietary goals, or maintaining a visual food journal.

## Key Features

- **Photo Logging** - Log meals with photos from camera or gallery for a visual food diary.

- **Detailed Notes** - Add comprehensive notes to each food entry for context and tracking.

- **Date Filtering** - Browse complete food history with powerful date filtering options.

- **PDF Reports** - Generate professional PDF reports for sharing with healthcare providers.

- **Email Sharing** - Share logs via email directly with dietitians and nutritionists.

- **Privacy-First** - All data stays on your device with no cloud storage or tracking.

- **Clean Interface** - Intuitive design with no complicated setup required.

## Architecture

Simple Food Log uses Feature-Oriented Architecture (FOA) with a clean 4-layer structure:

- **Domain Layer** - Pure business entities
- **Data Layer** - Drift SQL database implementation
- **Application Layer** - Services orchestrating repositories
- **Presentation Layer** - UI with Riverpod state management

## Technical Stack

- **Flutter 3.35+** with Dart
- **Riverpod 3.0** for state management with code generation
- **Drift** for type-safe SQL database
- **GoRouter** for navigation
- **RevenueCat** for optional monetization

*Currently preparing for App Store release.*
