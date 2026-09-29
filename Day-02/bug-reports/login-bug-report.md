# SauceDemo Login Bug Report

## Bug Title

Account is not locked after multiple failed login attempts

## Module

Login

## Environment

Web Application — Chrome Browser

## Severity

High

## Priority

High

## Precondition

A valid SauceDemo user account is available.

## Steps to Reproduce

1. Open the SauceDemo login page.
2. Enter a valid username.
3. Enter an incorrect password.
4. Click the **Login** button.
5. Repeat the failed login attempt multiple times.

## Test Data

**Username:** Valid registered username
**Password:** Incorrect password

## Expected Result

The system should restrict or temporarily lock the account after multiple consecutive failed login attempts.

## Actual Result

The user can continue making failed login attempts without an account lock or attempt limit.

## Status

Open

## Evidence

The bug was documented and tracked in Jira.
