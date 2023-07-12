# Overview
To Build lots of API Connectors for retrieving necessary information and for analysis purposes

List of supported connectors

- [x] Gmail API

## GMail API Overview

To connect to Gmail via OAuth2 and list the top ten senders for that particular email address.

### Workflow

1. **Authentication**: The tool will employ the OAuth2 protocol to establish a secure connection with the Gmail API. This process ensures that the user grants explicit permission for the tool to access their Gmail account.

2. **Authorization**: Once the user authorizes the tool, it will receive an access token and, if requested, a refresh token. These tokens will be used to authenticate subsequent API requests.

3. **Retrieve Top Senders**: Using the authorized access, the tool will query the Gmail API to retrieve the list of email messages associated with the user's account.

4. **Display Results**: The tool will present the some analytics to the user, allowing them to visualize.

<!-- ### Future Enhancements

If the initial POC proves successful, our client intends to expand the tool's functionality by incorporating additional features. Some potential enhancements include:

- **Unwanted Email Cleanup**: The tool can be extended to automatically detect and clean up unwanted emails by implementing filters based on predefined criteria.

- **Email Organization**: The tool could provide options for organizing emails into folders or labels based on sender, subject, or other custom criteria.

- **Advanced Search and Filtering**: Enhancing the search capabilities of the tool would allow users to perform advanced searches based on various criteria, such as sender, subject, date range, or keywords.

- **Email Analytics**: Adding analytics functionality would enable users to gain insights into their email usage patterns, such as email volume over time, response rates, or peak activity periods.

Overall, the goal of the email cleanup tool is to simplify and streamline the process of managing emails. By starting with a basic POC focused on authorization and retrieving top senders, our client can validate the concept and gradually expand the tool's capabilities based on user feedback and requirements. -->