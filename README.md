# design_patterns_in_react
Learning about Design Patterns in React

Following the tutorial

https://www.youtube.com/playlist?list=PLApy4UwQM3Updrw-4mOXTwgsWar9bqk6i

AGENDA
1. Single Responsibility Principle
   Every single Component should be responsible for only one thing and will delegate everything else to other Components.

   - HomePage - fetching posts
   - PostFeed - rendering a list of PostCards
   - PostCard - rendering a Card with a post

   - EmailInputRow
   - PasswordInputRow
   - SignInButtonRow
   npx mightymeld

2. Page Components, Feature Components, UI Components, Compound Components

   SignInForm (validation, handleSubmit, Card with form) - Feature Component - these are made almost always from smaller Components (Card)
   SignInPage (useEffect (for example for Analytics)) - Page Component
   SelectComponent (could make use of ContextAPI) - UI Component - creating Context, passing it to <select></select>
   OptionComponent (could make use of UI Component Context) - Compound Component - creating Context, passing it to <option></option>

3. Extraction into Hooks, even if they are not reusable.
