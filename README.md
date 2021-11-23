# Digital Surger Android Tech Test

We would like you to spend a few hours on the following technical task:

Create an app with two screens:

### Procedure Page
This should be the home page of the app. It should have a list of procedures cards/cells, each with a thumbnail image and a name. This information can be acquired from the [procedures endpoint](#Endpoints). Clicking on one of the procedure cards/cells should take the user to the next page.

### Procedure Details Page
This page should present the details of the procedure selected. There should be a card image at the top of the page, the title of the procedure and then the list of phases for the procedure. Each phase should contain a thumbnail image and a name. This information can be acquired from the [procedure details endpoint](#Endpoints) with the procedure id as a parameter, e.g procedures/procedure-ETH_WedgeRes

## Instructions:
- This is your fork of the project. Feel free to push to main.
- Upon completion, email us to let us know you have finished.
- Do not include build folders or IDE specific files.

## Endpoints
- The procedures list will be available at `https://staging.touchsurgery.com/api/v3/procedures` 
- Procedure details are available at `https://staging.touchsurgery.com/api/v3/procedures/$PROCEDURE_ID`

For example `https://staging.touchsurgery.com/api/v3/procedures/procedure-TSC_CemCup`

## Technologies to use:
You will be joining an existing team with existing technology. We are interested in gauging how well you use those technologies, so if we do not see them addressed here we will discuss them in the interviews. These technologies include, but are not limited to: 
Dependency injection with Dagger/Hilt, Room, Coroutines, Retrofit, UI testing with Espresso, MVVM, and unit testing.
We do not expect you to be able to come in on day one and do everything straight away, but familiarity with these technologies helps significantly, especially for senior candidates.
We are interested in how you architect mobile applications so pay attention to which design pattern to use and be prepared to answer questions about why you chose the pattern you did.
A good architecture would be highly appreciated.

## Automated tests:
Please make sure that you write your code in a testable way and that you include some unit tests. TDD is a tool that we use when we feel it is appropriate. We want to respect your time and do not expect 100% coverage, but would some examples of representative unit testing. The same goes for UI tests.

## Persistence:
Please write a few paragraphs on how you would handle data persistence / caching for use when offline. There are many ways to address this problem, we would be interested in hearing about your prefered approach. Examples of how you have solved this issue in the past would be helpful.
