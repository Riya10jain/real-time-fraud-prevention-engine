# Real-Time Fraud Prevention Engine

A Java-based fraud detection prototype designed to evaluate transaction details, identify potentially suspicious activities, and classify transactions based on their risk level.

## Overview

The Real-Time Fraud Prevention Engine aims to improve transaction security by analyzing transaction-related information and assigning a risk score.

Based on the calculated risk level, the system provides one of three decisions:

- **Approve:** Transaction has a low risk score.
- **Review:** Transaction requires additional verification.
- **Block:** Transaction has a high risk score.

This project demonstrates the basic concept of fraud detection and risk assessment.

## Features

- Transaction information analysis
- Risk score generation
- Fraud risk classification
- Approve, Review, and Block decisions
- Backend processing using Java and Spring Boot
- REST API-based architecture
- MySQL database integration

## Tech Stack

| Technology | Purpose |
|---|---|
| Java | Backend programming |
| Spring Boot | Backend framework |
| REST APIs | Communication |
| MySQL | Database |
| Maven | Dependency management |

## How It Works

1. The user provides transaction-related details.
2. The system receives the transaction information.
3. The backend analyzes the available parameters.
4. A risk score is generated.
5. The transaction is classified into one of three categories:
   - Approve
   - Review
   - Block

## Risk Assessment

The system considers transaction-related factors such as:

- Transaction amount
- Device information
- Location details
- Transaction frequency

The risk assessment helps identify potentially suspicious transaction patterns.

## Project Structure

```text
real-time-fraud-prevention-engine/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   └── resources/
│   │
│   └── test/
│
├── pom.xml
└── README.md
```

*Note: The structure above is illustrative. Actual folders may vary depending on the implementation.*

## Project Status

**Status:** Prototype / Development Project

This project demonstrates the concept of transaction risk assessment. It is not currently integrated with a live payment gateway.

## Future Enhancements

- Integration with real payment gateways
- Advanced machine learning-based fraud detection
- Real-time transaction monitoring
- Improved fraud detection accuracy
- User authentication and transaction history

## Author

**Riya Jain**

GitHub: [Riya10jain](https://github.com/Riya10jain)

---

If you find this project interesting, feel free to explore the repository!
