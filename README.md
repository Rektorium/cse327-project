**Project Summary: Club Event Management System**

The Club Event Management System is a web-based platform designed to streamline the management and viewing of events hosted by various clubs. Built using the Flask framework (Python) and powered by a SQL Server database, this system enables users to efficiently create, update, and retrieve information about events, clubs, and users through a set of APIs.

**Key Features:**

    Events API:
        Enables users to browse all events, view detailed event information, and create new events.
        Event details include the event name, type, date, day, start and end times, venue, contact information (email and phone), budget, ticketing details, and event images.

    Clubs API:
        Provides data about all clubs, including their names, types, faculty coordinators, contact information, activities, total number of events, and photo viewer links.

    User API:
        Handles user management for different roles, such as student members, faculty members, and student welfare members, each associated with specific clubs.

    Event Approval Workflow:
        Events are categorized into statuses such as 'Pending,' 'Approved,' or 'Denied.'
        Active events are displayed until their scheduled dates, after which they are archived under past events.

    Event Creation API:
        Authorized users can create new events by submitting relevant details, including images and URLs.

**Database Structure:**

The system uses a SQL Server database with the following key tables:

    Events: Stores event-related data, including status and detailed descriptions.
    Clubs: Contains club-specific information.
    Users: Divided into three tables for students, faculty, and student welfare members, with data linking users to their respective clubs.

**Conclusion:**

The Club Event Management System provides a comprehensive and scalable solution for managing club events. Its API-driven architecture facilitates seamless integration with other systems while ensuring flexibility and efficiency. By simplifying event organization and offering robust features, the platform serves as a valuable tool for event organizers.
