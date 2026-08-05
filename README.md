# Secure Chat Application

A secure client-server chat application developed using C# .NET, focusing on real-time communication and cybersecurity concepts.

## Overview

Secure Chat Application is a desktop-based messaging system that enables users to communicate through a client-server architecture.

The project focuses on implementing security mechanisms including encryption, authentication, access control, and database security to protect user data and communication.

## Features

### Authentication & User Management
- User registration and login
- Account management
- Password protection using hashing techniques
- OTP-based verification

### Real-time Communication
- Client-server communication using TCP Socket
- Real-time message exchange
- Support for multiple client connections

### Security Mechanisms

#### Encryption
- AES encryption for securing message data
- RSA encryption for secure key exchange

#### Access Control
- Role-Based Access Control (RBAC)
- Mandatory Access Control (MAC)

#### Database Security
- Oracle Database integration
- Virtual Private Database (VPD)
- Row-Level Security (RLS)
- Database auditing

## System Architecture

Client Application | | TCP Socket | | Server Application | | Oracle Database

## Technologies Used

- **Programming Language:** C#
- **Framework:** .NET Framework / .NET
- **Database:** Oracle Database
- **Networking:** TCP Socket Programming
- **Security:** AES, RSA, Password Hashing, RBAC, MAC, VPD, Auditing

## Installation

### Requirements

- Visual Studio
- .NET Framework
- Oracle Database

### Setup

1. Clone this repository:

```bash
git clone <repository-url>
2. Configure the Oracle Database connection.
3. Open the solution file using Visual Studio.
4. Build and run the Server application.
5. Run the Client application.
```
