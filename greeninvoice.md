# Green Invoice MCP Server

[![API Documentation](https://img.shields.io/badge/API%20Docs-Green%20Invoice-brightgreen)](https://www.greeninvoice.co.il/api-docs/)
[![Postman Collection](https://img.shields.io/badge/Postman-Collection-orange)](https://app.getpostman.com/run-collection/bd95f41eb3146ab4ecdb)

## Overview

Green Invoice is a popular invoicing platform in Israel that provides a comprehensive public API for integration. This document outlines plans for creating an MCP server that would allow AI systems to interact with Green Invoice services.

## API Resources

The Green Invoice API provides functionality for:

- Creating and managing invoices
- Managing customers and contacts
- Handling payments
- Generating financial reports
- Managing business settings

## MCP Server Implementation Plan

### Proposed Tools

1. **create-invoice**: Create a new invoice for a specified customer
2. **get-invoice**: Retrieve invoice details by ID
3. **list-invoices**: List invoices with optional filtering
4. **manage-customers**: Create, update, or retrieve customer information
5. **generate-reports**: Generate financial reports for specified time periods

### Resources to Expose

1. **invoice-templates**: Access to available invoice templates
2. **business-settings**: Access to business configuration
3. **customer-data**: Access to customer information

## Implementation Notes

- Authentication will require API key management
- Rate limiting considerations should be implemented
- Data privacy and security measures must be robust
- Webhook integration for real-time updates

## References

- [Green Invoice API Documentation](https://www.greeninvoice.co.il/api-docs/)
- [Postman Collection](https://app.getpostman.com/run-collection/bd95f41eb3146ab4ecdb)

## Status

- [ ] Initial research
- [ ] API endpoint mapping
- [ ] Tool definitions
- [ ] Resource definitions
- [ ] Authentication implementation
- [ ] Testing framework
- [ ] Documentation
