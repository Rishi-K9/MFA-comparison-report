# Multi-Factor Authentication (MFA) Comparison Report

## Project Overview

This project explains Multi-Factor Authentication (MFA) and compares the three major authentication factors: knowledge, possession, and inherence.

The purpose of this project is to understand how MFA improves account security and why using multiple authentication factors provides stronger protection than relying on a single factor.

## Objective

The objective of this project is to:

- Understand the concept of Multi-Factor Authentication.
- Learn about different authentication factors.
- Compare knowledge, possession, and inherence factors.
- Understand how MFA improves account security.
- Determine whether an OTP alone qualifies as MFA.

## Authentication Factors

Authentication factors are categories of information or evidence used to verify a user's identity. The three common authentication factors are knowledge, possession, and inherence.

### 1. Knowledge Factor

A knowledge factor is something the user knows.

Examples:
- Password
- PIN
- Security question
- Passphrase

A password is a common example of a knowledge factor. However, passwords can be stolen, guessed, or exposed through phishing attacks.

### 2. Possession Factor

A possession factor is something the user has.

Examples:
- Mobile phone
- Hardware security key
- Authentication token
- Smart card

For example, an OTP sent to a registered mobile device can be used as a possession factor when the device is trusted as something the user possesses.

### 3. Inherence Factor

An inherence factor is something the user is. It is based on a person's biometric characteristics.

Examples:
- Fingerprint
- Face recognition
- Iris recognition
- Voice recognition

Biometric authentication can make account access more difficult for an attacker because biometric characteristics are associated with the individual.


## MFA Factor Comparison

| Authentication Factor | What It Means | Examples | Main Advantage | Main Risk |
|---|---|---|---|---|
| Knowledge | Something the user knows | Password, PIN, Passphrase | Simple and easy to use | Can be guessed, stolen, or exposed |
| Possession | Something the user has | Mobile phone, Security key, Smart card | Adds a physical verification step | Device or token can be lost or compromised |
| Inherence | Something the user is | Fingerprint, Face recognition, Iris scan | Difficult to replicate remotely | Biometric data cannot be easily changed if compromised |

## How MFA Improves Account Security

Multi-Factor Authentication improves account security by requiring two or more independent authentication factors before granting access to an account.

If an attacker obtains a user's password, MFA can prevent unauthorized access because the attacker may still need another factor, such as a registered device, security key, or biometric verification.

MFA helps protect accounts against common threats such as:

- Password theft
- Credential stuffing
- Phishing
- Brute-force password attacks
- Unauthorized account access

For example, if a user has a password and a separate authentication factor, stealing only the password is not enough to complete the authentication process.

### Benefits of MFA

- Provides an additional layer of security.
- Reduces the impact of stolen passwords.
- Makes unauthorized access more difficult.
- Helps protect sensitive accounts and information.
- Provides stronger security than password-only authentication.

## Is OTP Alone MFA?

An OTP (One-Time Password) is not automatically Multi-Factor Authentication.

MFA requires authentication using two or more different authentication factors. If an OTP is used as the only authentication method, it is considered single-factor authentication.

For example:

- Password + OTP = MFA, because it combines a knowledge factor and a possession factor.
- OTP only = Single-factor authentication.
- Password + Fingerprint = MFA, because it combines a knowledge factor and an inherence factor.

Therefore, an OTP alone is not MFA. It becomes part of MFA when it is combined with another independent authentication factor.

## MFA Examples

### Example 1: Password + OTP

A user enters a password and then provides an OTP received on their registered device.

Factors used:
- Knowledge: Password
- Possession: Registered device

This is MFA because two different authentication factors are used.

### Example 2: Password + Fingerprint

A user enters a password and then verifies their fingerprint.

Factors used:
- Knowledge: Password
- Inherence: Fingerprint

This is MFA because two different authentication factors are used.

### Example 3: Password Only

A user signs in using only a password.

Factor used:
- Knowledge: Password

This is not MFA because only one authentication factor is used.

