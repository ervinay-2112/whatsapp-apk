# Prisma Database Schema

## Overview
This Prisma schema defines the complete database structure for the WiFi Customer Renewal Management System.

## Tables

### User
- Stores admin and staff users
- Supports role-based access control
- Tracks login history

### Customer
- Core customer information
- Plan and subscription details
- Connection and router details

### Plan
- Predefined internet plans
- Speed, price, and duration configurations

### Renewal
- Tracks all customer plan renewals
- Links old and new plans
- Payment and invoice generation

### Payment
- Payment transaction records
- Multiple payment method support
- Status tracking

### Invoice
- Invoice generation and tracking
- Tax calculations
- Payment status

### MessageLog
- WhatsApp, SMS, Email, Push notification logs
- Delivery tracking
- Retry mechanism

### Notification
- In-app notifications
- Read/unread status
- Action URLs

### ReminderLog
- Automated reminder tracking
- 5 reminder types (7 days, 3 days, today, overdue 3 days, overdue 7 days)
- Status and execution tracking

### Setting
- Application-wide settings
- Configuration management
- Secret value support
