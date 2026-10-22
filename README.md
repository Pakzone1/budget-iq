# Budget IQ

**Local-first expense tracking with AI-assisted text and voice entry.**

## The problem

Spending money is easy. Recording it apparently needs a category, an amount, a date, and several taps. As if the payment itself was not enough admin.

Budget IQ reduces that friction by turning everyday text and speech into financial entries that users can review, while keeping ordinary tracking useful offline.

## The solution

A Flutter app for expenses, income, budgets, and spending insights, combining a local database with optional cloud-backed account features and AI entry assistance.

## What it does

- Manual, text, and voice entry through a shared review flow.
- Expense/income records, budgets, and transaction history.
- Parsing for English, Urdu, Punjabi, and mixed-language input.
- AI-assisted insights and budget planning.
- Local persistence with account backup/sync workflows.
- Subscriptions and server-side AI quota enforcement.

## Engineering highlights

Combines currency-aware records, account-safe local archives, shared entry/review flows, and server-enforced AI entitlements. UI simplification brings frequent actions into a focused interface while retaining purposeful motion and accessible layouts.

## Technology

Flutter, Riverpod, Drift/SQLite, Firebase Auth/Firestore/Cloud Functions, Groq, RevenueCat.

## Source code

This repository documents the project, its capabilities, and the engineering behind it. The application source code is maintained privately.
