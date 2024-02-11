# Flask-application-2

# Common Vulnerabilities and Exposures (CVEs) Management System

This Flask application provides an API for managing data related to Common Vulnerabilities and Exposures (CVEs). It allows users to retrieve, add, update, and delete CVE records from a database.

## API Endpoints

### GET /cve/all
Retrieves all CVE data from the database. Returns a JSON array containing details of all CVEs.

### POST /cve/addCVE
Adds a new CVE record to the database with the provided data in the payload. Requires a JSON payload containing details of the new CVE record.

### DELETE /cve/<cve_id>
Deletes the CVE record identified by its CVE-ID from the database. Requires the CVE-ID as a path parameter.

### PUT /cve/<cve_id>
Modifies the details of a CVE identified by its ID with the provided data in the payload. Requires the CVE-ID as a path parameter and a JSON payload containing the updated details of the CVE.

## Error Handling
The application handles errors appropriately for each API endpoint. For example, if a requested CVE ID does not exist, the endpoints return an appropriate error response. Additionally, validation errors in the payload data are handled with informative error messages.

For detailed usage instructions and information on setting up the application, refer to the documentation or code comments.

--- 

In this README.md file, I've provided a brief overview of the application, listed the API endpoints along with their functionalities, and mentioned the error handling mechanism. This README should help users understand how to interact with the API and what to expect from it.
