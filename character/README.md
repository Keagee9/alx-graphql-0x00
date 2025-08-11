GraphQuest: Exploring and Implementing GraphQL
This repository contains my work for the "GraphQuest" project, focusing on fundamental concepts and practical implementation of GraphQL. The project is designed to help learners understand how to construct and execute GraphQL queries.

Task 0: Write a Query to Get a Specific Character by ID
Objective:
The goal of this task was to learn how to write a GraphQL query to retrieve the details of a specific character from an API using their unique ID. This is a foundational skill in working with GraphQL, demonstrating how to use arguments to fetch precise data.

Instructions:

A GraphQL query was written using the character(id: ID!) field.

The queries were designed to fetch character details for IDs 1, 2, 3, and 4.

Include the following fields in your query: `id`, `name`, `status`, `species`, `type`, `gender`.

Files:

character/character-id-1.graphql: Query for character with ID 1.

character/character-id-1-output.json: The expected JSON output for character ID 1.

character/character-id-2.graphql: Query for character with ID 2.

character/character-id-2-output.json: The expected JSON output for character ID 2.

character/character-id-3.graphql: Query for character with ID 3.

character/character-id-3-output.json: The expected JSON output for character ID 3.

character/character-id-4.graphql: Query for character with ID 4.

character/character-id-4-output.json: The expected JSON output for character ID 4.

Task 1: Write a Query to Get a List of All Characters
Objective:
Learners will create a GraphQL query to retrieve a paginated list of all characters.

Instructions:

Write a GraphQL query using the `characters(page: Int)` field to fetch the list of characters.

Create queries for pages 1, 2, 3, and 4.

Select the subfields: `id`, `name`, `status`, and `image`.

Files:

`character/all-characters-page-1.graphql`: Query for the first page of characters.
`character/all-characters-page-2.graphql`: Query for the second page of characters.
`character/all-characters-page-3.graphql`: Query for the third page of characters.
`character/all-characters-page-4.graphql`: Query for the fourth page of characters.