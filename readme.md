#  Brush up your Reactjs knowledge for your 2023 interview with this list of 50+ frequently asked questions


## Table of Contents
<div id="top"></div>

- [1. What is role of react in software development ?](#q1)
- [2. What is single page Application ?](#q2)
- [3. What are the advantage of react ?](#q3)
- [4.  What is the typical folder structure of a React.js application? ?](#q4)
- [5. Why is organizing your React.js application's folder structure important? ?](#q5)
- [6. What is the purpose of the "public" folder in a React.js application ?](#q6)
- [7. What is typically found inside the "src" folder of a React.js application ?](#q7)
- [8.  What is the purpose of the "index.js" file usually found inside a component folder? ?](#q8)
- [9. In a large-scale application, what strategies could you implement to prevent the folder structure from becoming overly complex and difficult to manage ?](#q9)
- [10. What is role of src folder in reactjs ?](#q10)
- [11. What is JSX in react ?](#q11)
- [12. What are the disadvantage of JSX ?](#q12)
- [13. What is transpiler in reactjs ?](#q13)
- [14. Difference between library and framwork ?](#q14)
- [15. What are props in React? ?](#q15)
- [16. Can props be modified inside a child component ?](#q16)
- [17. What is state in React ?](#q17)
- [18. When should you use state versus props ?](#q18)
- [19. What is a React component ?](#q19)
- [20. Explain the difference between functional and class components ?](#q20)
- [21. What is the Virtual DOM in React ?](#q21)
- [22. How does the Virtual DOM work ?](#q22)
- [23. Why does React use the Virtual DOM ?](#q23)
- [24. How does the reconciliation process work in React ?](#q24)
- [25. What's the benefit of using the Virtual DOM for rendering ?](#q25)
- [26. Can the Virtual DOM eliminate all performance bottlenecks ?](#q26)
- [27. Does React update the entire Virtual DOM on every state change ?](#q27)
- [28. How does the key attribute affect the Virtual DOM reconciliation process? ?](#q28)
- [29. Are there cases where using the Virtual DOM might be unnecessary ?](#q29)
- [30. what is diffing and Reconciliation ?](#q30)
- [31. What is difference between client side rendering and server side rendering ?](#q31)
- [32. What are React Hooks ?](#q32)
- [33. What problem do React Hooks solve ?](#q33)
- [34. How does the useState hook work ?](#q34)
- [35. Explain the useEffect hook ?](#q35)
- [36. What is the useContext hook used for ?](#q36)
- [37. How can custom hooks be used ?](#q37)
- [38. What's the purpose of the useMemo and useCallback hooks ?](#q38)
- [39. Can you use hooks in class components ?](#q39)
- [40. Why should we not update the state directly ?](#q40)
- [41. What is difference bewteen state and props  ?](#q41)
- [42. What is useRef  being uesd for ?](#q42)
- [43. What is pure Components and what is their purpose ?](#q43)
- [44. Why react uses className over class attribute ?](#q44)
- [45. What is React Fiber? ?](#q45)
- [46. What is the main goal of React Fiber ?](#q46)
- [47. What is controlled Compoments  ?](#q47)
- [48. What is uncontrolled Compoments  ?](#q48)
- [49. What are the difference between controlled and uncontrolled components ?](#q49)
- [50. What is Lifting State Up in React? ?](#q50)
- [51. What are Higher-Order Components ?](#q51)
- [52. What is context? ?](#q52)
- [53. what is prop drilling ?](#q53)
- [54. What are the several drawbacks of prop drilling ?](#q54)
- [55. What are the approaches used to avoid prop drilling ?](#q55)
- [56. What are fragments ?](#q56)
- [57. What are the benefits of using fragments  ?](#q57)
- [58. Why fragments are better than container divs ?](#q58)
- [59. What are stateless components ?](#q59)
- [6.  ?](#q6)






<div id="q1"></div>

## 1. What is role of react in software development ? [&uarr; Top](#top)
React is a popular JavaScript library primarily used for building user interfaces (UIs) in web applications. Its main role in software development is to provide a efficient and modular way to create interactive, dynamic, and responsive user interfaces. Here's a breakdown of the roles and features of React in software development:

1. **Component-Based Architecture**: React follows a component-based architecture, where the UI is broken down into reusable and independent components. Each component encapsulates its own logic, styles, and behavior, making it easier to manage and maintain complex UIs.

2. **Declarative Syntax**: React uses a declarative approach to define how the UI should look based on the current application state. Developers specify what they want the UI to look like, and React takes care of updating the DOM efficiently to match that desired state.

3. **Virtual DOM**: React introduces the concept of a Virtual DOM, which is an in-memory representation of the actual DOM. When the application's state changes, React calculates the difference (diff) between the current Virtual DOM and the previous one, and then updates the actual DOM only with the necessary changes. This minimizes DOM manipulation and enhances performance.

4. **Efficient Updates**: React employs a diffing algorithm to identify the minimal set of changes required to update the UI. This process makes updates efficient and helps in maintaining smooth user experiences, especially in applications with complex UIs.

5. **Unidirectional Data Flow**: React enforces a unidirectional data flow. Data flows in a single direction, from parent components to child components. This makes it easier to trace how data changes affect the UI, enhancing predictability and maintainability.

6. **Reusability and Composition**: React's component architecture promotes reusability. Developers can create small, self-contained components and compose them to build larger, more complex UIs. This makes it easier to maintain and update different parts of an application separately.

7. **State Management**: While React itself manages component state, for more complex applications, additional state management libraries like Redux or MobX are often used to handle application-wide state and data flow.

8. **React Hooks**: Introduced in React 16.8, hooks provide a way to use state and other React features without writing class components. Hooks like `useState`, `useEffect`, and `useContext` enable functional components to manage state and side effects.

9. **Community and Ecosystem**: React has a vibrant community and a vast ecosystem of third-party libraries and tools that enhance development. This includes tools for routing, form handling, styling (such as styled-components), and more.

10. **Cross-Platform Development**: While React is primarily used for web development, frameworks like React Native leverage the same component-based architecture to build native mobile applications for iOS and Android platforms.


<div id="q2"></div>

## 2. What is single page Application? [&uarr; Top](#top)
A Single Page Application (SPA) is a web app that loads once and dynamically updates content as users interact. Unlike traditional multi-page apps, SPAs use JavaScript frameworks for dynamic UI changes and client-side routing. They offer smoother user experiences by avoiding full-page reloads and relying on APIs to fetch data. SPAs are built with frameworks like React, Angular, or Vue.js, improving responsiveness and reducing latency.

<div id="q3"></div>

## 3. What are the advantage of react ? [&uarr; Top](#top)
React offers several advantages that make it a popular choice for building user interfaces in web applications:

1. **Component-Based Architecture**: React follows a component-based approach, allowing developers to create modular and reusable UI components. This promotes a clean code structure, easier maintenance, and efficient collaboration among team members.

2. **Declarative Syntax**: React uses a declarative syntax, where developers describe the desired UI state and React takes care of updating the DOM to match that state. This makes the code more readable and easier to understand.

3. **Virtual DOM**: React's Virtual DOM optimizes performance by updating only the necessary parts of the actual DOM. This minimizes unnecessary re-rendering, leading to better performance and smoother user experiences.

4. **Efficient Updates**: The Virtual DOM and React's reconciliation algorithm ensure that only the changed components are updated, reducing the overall number of DOM manipulations and enhancing performance.

5. **Reusability and Composition**: React's component structure encourages reusability. Components can be composed to build more complex UIs, and third-party libraries can easily integrate with React applications.

6. **React Hooks**: Introduced in React 16.8, hooks enable developers to use state and other React features in functional components, eliminating the need for class components. This simplifies code and promotes a more functional programming style.

7. **Community and Ecosystem**: React has a large and active community, resulting in a rich ecosystem of third-party libraries, tools, and resources that aid in development. This includes state management libraries like Redux, UI component libraries, and more.

8. **Cross-Platform Development**: React's principles are extended to React Native, allowing developers to use similar concepts to build native mobile applications for iOS and Android platforms.

9. **Strong Developer Tools**: React's developer tools, available as browser extensions, provide powerful debugging and inspection capabilities, helping developers understand component hierarchies, state changes, and performance bottlenecks.

10. **SEO-Friendly**: Although SPAs can face SEO challenges, React can be used with server-side rendering (SSR) or static site generation (SSG) to make content more accessible to search engines, improving SEO.

11. **Large Companies and Adoption**: React is backed by Facebook and is used by many large companies like Instagram, Airbnb, and Netflix. Its widespread adoption ensures continued development, support, and community engagement.

12. **Easy Learning Curve**: React's simple and focused API makes it relatively easy to learn, especially for developers familiar with JavaScript and basic web development concepts.

Overall, React's focus on performance, modularity, and developer experience, combined with its vibrant community and ecosystem, makes it a powerful tool for building modern, interactive, and efficient user interfaces.

<div id="q4"></div>

## 4.  What is the typical folder structure of a React.js application? ? [&uarr; Top](#top)
The typical folder structure of a React.js application includes folders like "src" for source code, "public" for static assets, and additional folders to organize components, styles, and more.

<div id="q5"></div>

## 5. Why is organizing your React.js application's folder structure important? [&uarr; Top](#top)
A well-organized folder structure promotes maintainability, scalability, and collaboration. It makes it easier to find and update specific files, components, and assets as the application grows.

<div id="q6"></div>

## 6. What is the purpose of the "public" folder in a React.js application? [&uarr; Top](#top)
The "public" folder holds static assets like HTML files, images, and fonts. The "index.html" file inside this folder is the entry point for the application and typically contains a root element where React components are rendered

<div id="q7"></div>

## 7. What is typically found inside the "src" folder of a React.js application ? [&uarr; Top](#top)
The "src" folder contains the main source code of the React application. This includes JavaScript files for components, styles, utility functions, and any other code related to the app's functionality

<div id="q8"></div>

## 8.  What is the purpose of the "index.js" file usually found inside a component folder?? [&uarr; Top](#top)
The "index.js" file in a component folder acts as the entry point for that component. It can export the component, making it more convenient to import in other parts of the application

<div id="q9"></div>

## 9. In a large-scale application, what strategies could you implement to prevent the folder structure from becoming overly complex and difficult to manage? ? [&uarr; Top](#top)
In a large-scale application, preventing the folder structure from becoming overly complex and difficult to manage is crucial for maintaining developer productivity and codebase maintainability. Here are several strategies that can be implemented:

1. **Modularization:** Break down the application into smaller, manageable modules. Each module should have a clear responsibility or feature. This helps distribute the complexity and makes it easier to understand and maintain each part of the application.

2. **Feature-Based Structure:** Organize the folder structure around features rather than technical concerns. Each feature or module should have its own directory with components, styles, assets, and related files. This promotes separation of concerns and reduces the chance of files becoming scattered across the codebase.

3. **Flat Directory Structure:** Avoid deep nesting of folders. A deep folder hierarchy can make it difficult to navigate and find files. Instead, opt for a flatter structure with a limited number of subdirectories.

4. **Consistent Naming Conventions:** Use clear and consistent naming conventions for files and folders. This makes it easier to identify the purpose of each file and locate them quickly.

5. **Clear Abstraction Levels:** Establish different abstraction levels for components. For instance, separate components into "atoms," "molecules," "organisms," and higher-level components. This promotes reusability and helps developers quickly identify where to find specific components.

6. **Documentation:** Provide clear documentation on how the folder structure is organized, the purpose of each directory, and any conventions followed. New developers should be able to understand the structure easily.

7. **Automated Tools:** Utilize code generation or scaffolding tools to create new components, modules, or features based on predefined templates. This enforces consistency and reduces the chance of manual errors.

8. **Refactoring:** Regularly revisit the folder structure as the application evolves. Refactor the structure if it's starting to feel unwieldy or if new patterns emerge that could improve organization.



<div id="q10"></div>

## 10. What is role of src folder in reactjs ? [&uarr; Top](#top)
In a React.js application, the "src" (source) folder plays a crucial role as it contains the main source code of the application. This is where most of the development work takes place. The "src" folder is considered the heart of the application and typically contains various subdirectories and files that collectively build the user interface and logic of the application

<div id="q11"></div>

## 11. What is JSX in react? [&uarr; Top](#top)
JSX stands for "JavaScript XML," and it is a syntax extension used in React.js applications. It allows you to write HTML-like code within your JavaScript code, making it easier to define and render React elements in a more declarative and intuitive manner.

JSX is not pure HTML; it's a syntax that gets transformed into JavaScript code before being interpreted by the browser. Here's how JSX works and its role in React:

1. **Declarative Syntax:** JSX provides a more declarative way to describe the structure of UI components. Instead of using complex JavaScript calls to create DOM elements, JSX allows you to write components using tags similar to HTML.

2. **Embedding Expressions:** You can embed JavaScript expressions within JSX by enclosing them in curly braces `{}`. This allows you to dynamically generate content and values based on data and logic.

3. **React Elements:** When JSX is processed by the React framework, it gets converted into plain JavaScript objects called "React elements." These elements represent the structure of the user interface and define how components should be rendered.

4. **Components:** JSX allows you to define and use custom components just like HTML tags. For example, if you have a `Button` component, you can use `<Button />` in JSX to render it.

5. **Attributes:** You can assign attributes to JSX elements just like in HTML. For example, `<img src="image.jpg" alt="An image" />`.

6. **Event Handling:** JSX supports event handling by using camelCase versions of event names. For example, `onClick` instead of `onclick`.

Here's an example of JSX in a React component:

```jsx
import React from 'react';

const Greeting = (props) => {
  return <h1>Hello, {props.name}!</h1>;
};

export default Greeting;
```

In this example, the `<h1>` element and the curly braces `{props.name}` are part of JSX. When this code is transpiled, it becomes equivalent to the following JavaScript code:

```javascript
import React from 'react';

const Greeting = (props) => {
  return React.createElement('h1', null, `Hello, ${props.name}!`);
};

export default Greeting;
```

In summary, JSX is a syntax extension used in React to write more readable and expressive code for creating UI components. It simplifies the process of defining and rendering React elements while still allowing you to embed dynamic JavaScript expressions.

<div id="q12"></div>

## 12. What are the disadvantage of JSX ? [&uarr; Top](#top)
While JSX offers numerous advantages for developing React applications, there are also some potential disadvantages to consider:

1. **Learning Curve for New Developers:** Developers who are new to React and JSX might find the syntax initially confusing, especially if they are not familiar with mixing HTML-like syntax with JavaScript expressions.

2. **Tooling and Build Process:** Using JSX requires setting up a build process or transpiler (like Babel) to convert JSX code into regular JavaScript that browsers can understand. This adds complexity to the development setup.

3. **Visual Overload:** JSX code can become visually overwhelming when components are deeply nested or include complex logic. The mix of HTML tags and JavaScript expressions might make it harder to read and maintain.

4. **Limited Template Editing Tools:** Traditional HTML editing tools or IDEs might not provide full support for JSX. This can result in incomplete or confusing code suggestions and auto-completions.

5. **Accessibility Challenges:** JSX might encourage developers to focus more on layout and visual aspects, potentially leading to less attention being paid to web accessibility best practices.




<div id="q13"></div>

## 13. What is transpiler in reactjs? [&uarr; Top](#top)
A transpiler, also known as a source-to-source compiler, is a tool that translates code from one programming language into another while preserving its functionality. In the context of React.js and JavaScript, a transpiler is used to convert modern JavaScript code, including features that might not be supported by all browsers, into a version of JavaScript that is compatible with a wider range of browsers.

The most popular transpiler used with React.js is Babel. Babel can convert JSX and modern JavaScript features (such as ES6 and beyond) into a version of JavaScript that is compatible with older browsers or environments. It also supports converting new JavaScript language features into their equivalent older versions, enabling developers to write code using the latest syntax while ensuring that it runs on a broader range of platforms.

Here's how the transpilation process works with React.js:

1. Developers write code, including JSX and modern JavaScript features, in their source files.

2. Babel, the transpiler, is configured to process these source files and apply transformations based on the specified presets and plugins.

3. Babel converts JSX into `React.createElement` calls and transforms modern JavaScript syntax into its equivalent ES5 or older JavaScript syntax.

4. The transpiled code is outputted into separate files, often in the same or a different directory, as specified in the build configuration.

5. The resulting transpiled code is what's included in the final build of the React application. This code can be executed by a wider range of browsers and environments.


<div id="q14"></div>

## 14. Difference between library and framwork? [&uarr; Top](#top)

**Library:**

1. Provides a collection of pre-written functions, classes, or modules.
2. Offers specific functionalities or tools that can be used as needed.
3. Leaves control over application structure and flow to the developer.
4. You decide when and how to use specific parts of the library.
5. Typically focuses on solving specific tasks or problems.
6. Examples include jQuery (DOM manipulation) and Axios (HTTP requests), Reactjs.

**Framework:**

1. Provides a comprehensive structure and guidelines for building applications.
2. Dictates the overall architecture and design of the application.
3. Controls the flow of the application, often following a predefined pattern.
4. You build the application within the framework's predefined structure.
5. Often encompasses various libraries and tools for different aspects of development.
6. Examples include Angular, Vuejs, and Django.



<div id="q15"></div>

## 15. What are props in React? [&uarr; Top](#top)
Props (short for "properties") are a mechanism for passing data from a parent component to a child component. They allow components to communicate and share information

<div id="q16"></div>

## 16. Can props be modified inside a child component? [&uarr; Top](#top)
No, props are immutable. They are meant to be read-only and should not be modified directly within the child component. If you need to change data, you should use state instead

<div id="q17"></div>

## 17. What is state in React ? [&uarr; Top](#top)
State is a built-in feature in React that represents the mutable data that a component can maintain. When the state changes, the component re-renders to reflect those changes.

<div id="q18"></div>

## 18. When should you use state versus props? [&uarr; Top](#top)
Use props when you need to pass data from a parent component to a child component. Use state when a component needs to manage its own mutable data that can change over time

<div id="q19"></div>

## 19. What is a React component? [&uarr; Top](#top)
A React component is a reusable and self-contained building block that encapsulates a piece of UI, logic, and state. Components can be combined to create complex user interfaces

<div id="q20"></div>

## 20. Explain the difference between functional and class components? [&uarr; Top](#top)
Functional components and class components are two types of components in React, each with its own characteristics and use cases:

**Functional Components:**

- Functional components are simpler and more concise. They are essentially JavaScript functions that take in props as arguments and return JSX elements.

- They don't have their own state or lifecycle methods, which makes them lighter and easier to understand.

- Functional components are ideal for presenting UI and handling simple logic that doesn't require complex state management.

- With the introduction of React Hooks, functional components can also handle state and lifecycle-like features, reducing the need for class components.

- They promote a more functional programming style and are recommended for most scenarios due to their simplicity and readability.

**Class Components:**

- Class components are defined as ES6 classes that extend `React.Component`. They have more features, including state, lifecycle methods, and access to the `this` keyword.

- They were the primary way to manage state and lifecycle in React before the introduction of Hooks.

- Class components are suited for more complex components that require state management, access to lifecycle methods, or optimization through `shouldComponentUpdate`.

- With the advent of Hooks, class components are becoming less common, and functional components with Hooks are preferred due to their simpler syntax and better performance.


<div id="q21"></div>

## 21. What is the Virtual DOM in React? [&uarr; Top](#top)
The Virtual DOM is an abstraction of the actual DOM (Document Object Model). It's a lightweight, in-memory representation of the UI. React uses the Virtual DOM to optimize and speed up the process of updating the actual DOM

<div id="q22"></div>

## 22. How does the Virtual DOM work ? [&uarr; Top](#top)
 When there's a change in the state of a React component, React creates a new Virtual DOM representation of the updated UI. It then performs a "diffing" process to identify the differences between the new Virtual DOM and the previous one. Only the necessary changes are applied to the actual DOM, minimizing the number of direct manipulations and improving performance

<div id="q23"></div>

## 23. Why does React use the Virtual DOM? [&uarr; Top](#top)
React uses the Virtual DOM for performance optimization. Directly manipulating the real DOM can be slow and resource-intensive. The Virtual DOM acts as a buffer between the developer's code and the actual DOM, allowing React to batch updates and minimize unnecessary re-renders.

<div id="q24"></div>

## 24. How does the reconciliation process work in React? [&uarr; Top](#top)
Reconciliation is the process of comparing the previous Virtual DOM with the new Virtual DOM to determine the minimal set of changes needed to update the actual DOM. React performs a top-down traversal of the component tree, identifying changes and applying updates efficiently

<div id="q25"></div>

## 25. What's the benefit of using the Virtual DOM for rendering ? [&uarr; Top](#top)
Using the Virtual DOM results in more efficient updates. It reduces the number of expensive DOM manipulations and improves application performance. Additionally, it abstracts away browser-specific behavior, providing a consistent programming interface.

<div id="q26"></div>

## 26. Can the Virtual DOM eliminate all performance bottlenecks? [&uarr; Top](#top)
 While the Virtual DOM greatly improves performance, it's not a silver bullet for all performance issues. React's reconciliation process can still be impacted by inefficient rendering logic, excessive component updates, and other factors.

<div id="q27"></div>

## 27.  Does React update the entire Virtual DOM on every state change? [&uarr; Top](#top)
 No, React updates only the parts of the Virtual DOM that have changed. This is achieved through the "diffing" process, which identifies the minimal set of changes needed for the update.

<div id="q28"></div>

## 28. How does the key attribute affect the Virtual DOM reconciliation process?? [&uarr; Top](#top)
The key attribute is crucial for React's reconciliation process. It helps React identify which components have changed, been added, or been removed when iterating over lists of elements. Properly using keys can significantly improve performance during updates.

<div id="q29"></div>

## 29. Are there cases where using the Virtual DOM might be unnecessary? [&uarr; Top](#top)
In some simple cases where the UI doesn't change frequently, using the Virtual DOM might introduce unnecessary overhead. However, React's efficient update mechanism is generally beneficial in most scenarios, even for relatively static UIs.

<div id="q30"></div>

## 30. what is diffing and Reconciliation? [&uarr; Top](#top)
**Diffing:**

Diffing refers to the process of comparing two versions of a tree-like data structure and identifying the differences between them. In the context of React, these data structures are the Virtual DOM representations of the UI before and after a state or prop change.

When React detects a change in the state or props of a component, it creates a new Virtual DOM representation of the updated UI. Then, it compares this new Virtual DOM with the previous one to determine what specific changes need to be made to the actual DOM to reflect the updated state.

**Reconciliation:**

Reconciliation is the process of applying the identified differences (diffs) between the old and new Virtual DOM representations to the actual DOM. It's the phase where React updates the UI to match the new state or props.

Reconciliation involves several steps, such as adding new nodes, removing nodes, and updating the attributes and content of nodes. React follows a "bottom-up" approach during reconciliation, starting from the leaves of the Virtual DOM tree and working its way up to the root.

The goal of reconciliation is to minimize the number of changes needed to update the UI. React's diffing algorithm ensures that only the necessary changes are applied, which helps improve the overall performance of the application by reducing unnecessary DOM manipulations.

In summary, diffing is the process of comparing two versions of the Virtual DOM to identify differences, and reconciliation is the process of applying those differences to the actual DOM. These processes are central to React's ability to efficiently update the UI in response to changes in state or props.

<div id="q31"></div>

## 31. What is difference between client side rendering and server side rendering? [&uarr; Top](#top)
Client-side rendering (CSR) and server-side rendering (SSR) are two different approaches to how web applications render and display content to users. Here's a concise comparison of the two:

**Client-Side Rendering (CSR):**

1. **Rendering Process:** In CSR, the initial HTML page is sent to the browser with minimal content and a JavaScript bundle. The JavaScript code executes in the browser, fetching data from APIs and rendering the complete UI.

2. **Page Load Speed:** CSR can result in slower initial page load times, as the browser needs to wait for the JavaScript to load, execute, and fetch data before rendering the full content.

3. **SEO Challenges:** Search engine crawlers might have difficulty indexing the content rendered by JavaScript, potentially affecting SEO. Proper techniques like server-side rendering or pre-rendering are needed for better SEO.

4. **User Experience:** Once the initial load is complete, CSR can provide a fast and responsive user experience, as interactions and subsequent page transitions are managed by JavaScript on the client side.

5. **Resource Efficiency:** CSR reduces server load during user interactions since most of the rendering work happens on the client side. However, the initial page load might require more client-side processing.

**Server-Side Rendering (SSR):**

1. **Rendering Process:** In SSR, the server generates the initial HTML page with the fully rendered content and sends it to the browser. JavaScript is then loaded, and the application is "hydrated" to add interactivity.

2. **Page Load Speed:** SSR typically results in faster initial page load times, as the browser receives pre-rendered content from the server. Users can see meaningful content sooner.

3. **SEO Benefits:** Since search engines receive fully rendered content from the server, SSR is inherently more SEO-friendly compared to CSR. The content is immediately available for indexing.

4. **User Experience:** While the initial load might be faster, interactions and subsequent page transitions might be slightly slower in SSR compared to CSR, as the browser may need to fetch additional data.

5. **Server Load:** SSR can increase server load, as the server needs to perform rendering for each request. Caching strategies and load balancing are commonly used to manage this.



<div id="q32"></div>

## 32. What are React Hooks ? [&uarr; Top](#top)
React Hooks are functions introduced in React 16.8 that allow you to use state and other React features in functional components. They enable you to "hook into" React state and lifecycle features without the need for class components.

Before Hooks, state management and lifecycle methods were primarily associated with class components. Hooks were introduced to address the challenges of reusing stateful logic across components and to simplify complex component structures.


React provides several built-in Hooks, including:

1. **useState:** Allows functional components to manage local state.

2. **useEffect:** Handles side effects (like data fetching, subscriptions, etc.) in functional components.

3. **useContext:** Enables functional components to access the context of a parent component.

4. **useReducer:** Provides an alternative to `useState` when dealing with more complex state logic.

5. **useMemo:** Memoizes the result of a computation to avoid unnecessary re-computation.

6. **useCallback:** Memoizes functions to prevent unnecessary re-creation of functions in renders.

7. **useRef:** Creates a mutable reference that persists across renders, useful for accessing DOM elements or holding values that don't trigger re-renders.

8. **Custom Hooks:** Allows you to create your own custom reusable hooks to encapsulate specific logic.

Using Hooks, developers can write more functional and modular code, reduce the need for higher-order components and render props, and avoid class component complexities. Hooks promote better separation of concerns and lead to more concise, readable, and maintainable code in React applications.

<div id="q33"></div>

## 33.  What problem do React Hooks solve? [&uarr; Top](#top)
 React Hooks address the issue of complex state management and logic in functional components. Previously, such logic was handled by class components and higher-order components, leading to less reusable and maintainable code

<div id="q34"></div>

## 34. How does the useState hook work? [&uarr; Top](#top)
The useState hook allows functional components to manage state. It returns a state variable and a function to update that state. Example
```jsx
import React, { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={() => setCount(count + 1)}>Increment</button>
    </div>
  );
}

```

<div id="q35"></div>

## 35. Explain the useEffect hook ? [&uarr; Top](#top)
 The useEffect hook allows you to perform side effects in functional components. It replaces lifecycle methods like `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount`. Example:
 ```jsx
import React, { useState, useEffect } from 'react';

function DataFetching() {
  const [data, setData] = useState([]);

  useEffect(() => {
    fetch('https://api.example.com/data')
      .then(response => response.json())
      .then(data => setData(data));
  }, []);

  return <ul>{data.map(item => <li key={item.id}>{item.name}</li>)}</ul>;
}

 ```

<div id="q36"></div>

## 36. What is the useContext hook used for ? [&uarr; Top](#top)
The useContext hook provides access to the context of a parent component. It eliminates the need to wrap components in Context.Consumer and simplifies the process of consuming context values. Example:
```jsx
import React, { useContext } from 'react';

const MyContext = React.createContext();

function Display() {
  const value = useContext(MyContext);
  return <p>{value}</p>;
}
```

<div id="q37"></div>

## 37.  How can custom hooks be used ? [&uarr; Top](#top)
Custom hooks are a powerful way to encapsulate and reuse logic in functional components in React. They allow you to extract common patterns or behaviors into a reusable function, making your code more modular and easier to maintain. Here's how you can use custom hooks:

**1. Create a Custom Hook:**

First, create a function that encapsulates the logic you want to reuse. Custom hooks follow the naming convention of starting with "use" to indicate that they are hooks. Here's a basic example of a custom hook:

```jsx
import { useState } from 'react';

function useCounter(initialValue) {
  const [count, setCount] = useState(initialValue);

  const increment = () => {
    setCount(count + 1);
  };

  return { count, increment };
}
```

**2. Use the Custom Hook:**

You can now use your custom hook in any functional component just like built-in hooks. Import and call your custom hook to access the logic it provides:

```jsx
import React from 'react';
import useCounter from './useCounter';

function CounterComponent() {
  const { count, increment } = useCounter(0);

  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={increment}>Increment</button>
    </div>
  );
}
```



<div id="q38"></div>

## 38. What's the purpose of the useMemo and useCallback hooks ? [&uarr; Top](#top)
`useMemo` memoizes the result of a computation so that it's only recomputed when its dependencies change. `useCallback` memoizes functions, which is useful to prevent unnecessary re-renders when passing functions as props to child components.

<div id="q39"></div>

## 39. Can you use hooks in class components ? [&uarr; Top](#top)
No, hooks are meant to be used exclusively in functional components. Class components continue to use lifecycle methods for state and side effects.

<div id="q40"></div>

## 40. Why should we not update the state directly ? [&uarr; Top](#top)
if you try to update the state directly then it won't re-render the component.
Instead use setState() method. It schedules an update to a component's state object. When state changes, the component responds by re-rendering

<div id="q41"></div>

## 41. What is difference bewteen state and props ? [&uarr; Top](#top)
Both props and state are plain JavaScript objects. While both of them hold information that influences the output of render, they are different in their functionality with respect to component. Props get passed to the component similar to function parameters whereas state is managed within the component similar to variables declared within a function.


<div id="q42"></div>

## 42. What is useRef  being uesd for? [&uarr; Top](#top)
`useRef` is a React Hook that provides a way to create a mutable reference that persists across renders of a functional component. It's primarily used for accessing DOM elements or holding values that don't trigger re-renders when they change.

Here are the common use cases for `useRef`:

1. **Accessing DOM Elements:** `useRef` allows you to directly access DOM elements in functional components. This is particularly useful when you need to interact with or manipulate DOM elements imperatively, like focusing an input field or measuring an element's dimensions.

   ```jsx
   import React, { useRef, useEffect } from 'react';

   function FocusInput() {
     const inputRef = useRef(null);

     useEffect(() => {
       inputRef.current.focus();
     }, []);

     return <input ref={inputRef} />;
   }
   ```

2. **Holding Values:** Unlike `useState`, changes to a `useRef` value won't trigger component re-renders. This makes it suitable for holding values that need to persist between renders but don't affect the UI.

   ```jsx
   import React, { useRef } from 'react';

   function CounterComponent() {
     const countRef = useRef(0);

     const increment = () => {
       countRef.current += 1;
       console.log('Current count:', countRef.current);
     };

     return (
       <div>
         <p>Click count: {countRef.current}</p>
         <button onClick={increment}>Increment</button>
       </div>
     );
   }
   ```

3. **Managing Previous Values:** `useRef` can be used to store previous values of props or state between renders, which can be helpful for comparing changes.

   ```jsx
   import React, { useRef, useEffect } from 'react';

   function ValueChangeLogger({ value }) {
     const prevValueRef = useRef();

     useEffect(() => {
       console.log('Previous value:', prevValueRef.current);
       prevValueRef.current = value;
     }, [value]);

     return <p>Current value: {value}</p>;
   }
   ```

Remember that changes to the `current` property of a `useRef` object won't trigger a re-render of the component. This property is mutable, but updating it doesn't cause the component to update or rerender. Therefore, `useRef` is often used for managing values or references that don't affect the visual rendering of the component.

<div id="q43"></div>

## 43. What is pure Components and what is their purpose? [&uarr; Top](#top)
A Pure Component in React is a class component that extends the React.PureComponent class. The primary purpose of using Pure Components is to optimize rendering performance by automatically performing a shallow comparison of the component's props and state. If there are no changes detected in the props or state, a Pure Component prevents unnecessary re-renders, which can lead to performance improvements

Pure components are also known as `functional components` or `stateless components` and they are defined by a function.

<div id="q44"></div>

## 44. Why react uses className over class attribute ? [&uarr; Top](#top)
React uses the className attribute instead of the class attribute because class is a reserved keyword in JavaScript. Using className avoids any confusion and ensures that the attribute will be interpreted as intended

<div id="q45"></div>

## 45. What is React Fiber? [&uarr; Top](#top)
Fiber is the new reconciliation engine or reimplementation of core algorithm in React v16. The goal of React Fiber is to increase its suitability for areas like animation, layout, gestures, ability to pause, abort, or reuse work and assign priority to different types of updates; and new concurrency primitives.

<div id="q46"></div>

## 46. What is the main goal of React Fiber ? [&uarr; Top](#top)
The goal of React Fiber is to increase its suitability for areas like animation, layout, and gestures. Its headline feature is incremental rendering: the ability to split rendering work into chunks and spread it out over multiple frames.
Its main goals are:

- Ability to split interruptible work in chunks.
- Ability to prioritize, rebase and reuse work in progress.
- Ability to yield back and forth between parents and children to support layout in React.
- Ability to return multiple elements from render().
- Better support for error boundaries

<div id="q47"></div>

## 47. What is controlled Compoments ? [&uarr; Top](#top)
a controlled component refers to a component whose value is controlled by the state of a parent component. This concept is important when working with form elements like input fields, checkboxes, and radio buttons in React.

In a controlled component, the value of the form element is not stored in the DOM, but rather in the component's state. When the user interacts with the form element, an event handler updates the component's state, which in turn causes the component to re-render with the updated value. This approach allows React to be the source of truth for the value of the form element, making it easier to manage and manipulate form data.

Here's a simple example using a controlled input component in React:
```jsx
import React, { useState } from 'react';

function ControlledInput() {
  const [inputValue, setInputValue] = useState('');

  const handleInputChange = (event) => {
    setInputValue(event.target.value);
  };

  return (
    <input
      type="text"
      value={inputValue}
      onChange={handleInputChange}
    />
  );
}
```

<div id="q48"></div>

## 48. What is uncontrolled Compoments ? [&uarr; Top](#top)
In an uncontrolled component, the component's value is not directly controlled by React state. Instead, the value is managed by the DOM itself. You can think of uncontrolled components as more traditional HTML form elements where you rely on the DOM to manage the state and retrieve the value when needed.

Here's an example using an uncontrolled input component in React:
```jsx
import React from 'react';

function UncontrolledInput() {
  const handleSubmit = (event) => {
    event.preventDefault();
    const inputValue = event.target.elements.myInput.value;
    console.log('Submitted value:', inputValue);
  };

  return (
    <form onSubmit={handleSubmit}>
      <input type="text" name="myInput" />
      <button type="submit">Submit</button>
    </form>
  );
}
```

<div id="q49"></div>

## 49. What are the difference between controlled and uncontrolled components  ? [&uarr; Top](#top)
Controlled Components and Uncontrolled Components are two approaches in React for managing the state of form elements and user input. Here are the key differences between the two:

1. **State Management:**
   - **Controlled Components:** The value of the form element (input, textarea, select) is controlled by React state. Changes to the value are controlled through event handlers, and the component re-renders whenever the state is updated.
   - **Uncontrolled Components:** The value of the form element is managed by the DOM itself. React does not control the value directly. Instead, you retrieve the value from the DOM using refs or DOM traversal.

2. **State Storage:**
   - **Controlled Components:** The value of the form element is stored in the React component's state. You set the initial value and update it using state updates.
   - **Uncontrolled Components:** The value of the form element is stored in the DOM. You access it using DOM manipulation methods.

3. **Event Handling:**
   - **Controlled Components:** You attach event handlers (like `onChange`) to the form elements to update the state. React handles the updates and re-renders the component.
   - **Uncontrolled Components:** You often rely on standard DOM events (like `onBlur` or `onSubmit`) to handle form interactions.

4. **Validation:**
   - **Controlled Components:** Easier to implement validation and controlled behavior, as all changes are mediated through React state and event handlers.
   - **Uncontrolled Components:** Validation and controlled behavior require additional custom logic, as React doesn't have direct control over the value.

5. **Accessing Form Values:**
   - **Controlled Components:** To access the current value of the form element, you use the corresponding state value.
   - **Uncontrolled Components:** You need to manually access the DOM element (using refs, querying the DOM, etc.) to retrieve the current value.

6. **Integration with React Ecosystem:**
   - **Controlled Components:** Align better with React's way of managing state and integrating with other React features.
   - **Uncontrolled Components:** May be useful when integrating with third-party libraries or working with older codebases that rely on direct DOM manipulation.


<div id="q50"></div>

## 50. What is Lifting State Up in React?? [&uarr; Top](#top)

"Lifting State Up" is a term used in React to describe the practice of moving the shared state of components higher up the component hierarchy so that multiple child components can access and modify that shared state. This is done to maintain a single source of truth for the state and to ensure that changes to the state are reflected consistently across all components that depend on it.

In React, each component has its own local state. However, there are cases where multiple components need to share some state or synchronize their behavior based on a common piece of data. Instead of duplicating the state in each component or relying on complex data passing through props, the state can be lifted up to a common ancestor component

<div id="q51"></div>

## 51. What are Higher-Order Components? [&uarr; Top](#top)
Higher-Order Components (HOCs) are a design pattern in React that allows you to reuse component logic and behavior in a more modular and flexible way. A Higher-Order Component is a function that takes a component and returns a new component with enhanced features or behaviors. It's a way to "wrap" or "decorate" components with additional functionality.

HOCs are not a built-in feature of React but rather a pattern made possible by the composability of React components. They provide a way to abstract and share common functionalities like data fetching, state management, authentication, and more, without duplicating code across multiple components

<div id="q52"></div>

## 52. What is context?? [&uarr; Top](#top)
In React, "context" refers to a feature that allows you to share data, such as state or other values, across components without explicitly passing the data through each component's props. It's a way to avoid "prop drilling," where you pass data through multiple layers of components just to get it to a deeply nested component that needs it.

React's Context API provides a way to create a context object that holds the shared data and allows components to access that data anywhere in the component tree, regardless of how deeply nested they are.

Here's a basic example of how React's Context API works:

```jsx
import React, { createContext, useContext } from 'react';

// Create a context
const MyContext = createContext();

// Provider component that holds the shared data
function MyContextProvider({ children }) {
  const sharedData = 'Hello from Context!';
  return <MyContext.Provider value={sharedData}>{children}</MyContext.Provider>;
}

// Component that consumes the shared data
function MyComponent() {
  const sharedData = useContext(MyContext);
  return <div>{sharedData}</div>;
}

// App component using the context provider
function App() {
  return (
    <MyContextProvider>
      <MyComponent />
    </MyContextProvider>
  );
}

export default App;
```



<div id="q53"></div>

## 53. what is prop drilling ? [&uarr; Top](#top)
Prop drilling, also known as "prop passing," is a term used to describe a situation in React where data or props need to be passed through multiple layers of nested components in order to reach a component that requires that data. This can happen when a deeply nested component needs access to some piece of information that is originally available higher up in the component tree.

Consider the following example:

```jsx
import React from 'react';

function GrandparentComponent({ data }) {
  return (
    <ParentComponent data={data} />
  );
}

function ParentComponent({ data }) {
  return (
    <ChildComponent data={data} />
  );
}

function ChildComponent({ data }) {
  return (
    <div>{data}</div>
  );
}

function App() {
  const data = "Hello, Prop Drilling!";
  return (
    <GrandparentComponent data={data} />
  );
}

export default App;
```

In this example, the `data` prop is passed from the `App` component to the `GrandparentComponent`, then from `GrandparentComponent` to `ParentComponent`, and finally from `ParentComponent` to `ChildComponent`. This process of passing the same prop down through multiple intermediate components is called prop drilling.

Prop drilling can lead to several drawbacks:

<div id="q54"></div>

## 54. What are the several drawbacks of prop drilling ? [&uarr; Top](#top)
1. **Complexity:** As your component tree becomes deeper, the need to pass props through multiple layers makes the codebase harder to understand and maintain.

2. **Maintenance:** If the prop name changes or additional data needs to be passed, you have to update the prop passing in multiple places.

3. **Redundancy:** Components in the middle of the hierarchy might not actually need the prop, but they're still responsible for passing it along.

To mitigate prop drilling, there are several approaches you can consider:

<div id="q55"></div>

## 55. What are the approaches used to avoid prop drilling ? [&uarr; Top](#top)
1. **Use Context:** If the prop is required by many components across different levels, consider using React's Context API to provide the data globally to components that need it, without having to explicitly pass the prop through each intermediate component.

2. **Higher-Order Components (HOCs):** Create a Higher-Order Component that wraps the components needing the prop. The HOC can inject the necessary props without the need for direct prop drilling.

3. **Custom Hooks:** Create a custom hook to encapsulate the logic and data-fetching for the prop. Components can then use this hook to access the data directly.

4. **State Management Libraries:** If the prop represents application-wide state, using a state management library like Redux or Mobx can centralize the data and reduce the need for prop drilling.

<div id="q56"></div>

## 56. What are fragments? [&uarr; Top](#top)
Fragments are a feature in React that allow you to group multiple elements without adding an additional DOM element to the rendered output. They provide a way to structure your components without introducing unnecessary wrapping elements in the DOM.

Before fragments were introduced, when you wanted to return multiple adjacent elements from a component, you had to wrap them in a parent element, like a `<div>`. However, this could sometimes lead to unnecessary DOM nesting and styling complications.

Fragments solve this problem by providing a way to group elements without introducing an extra DOM node. Fragments are not rendered themselves; they're just a way to group multiple elements under a single parent.

Here's an example of how fragments work:

```jsx
import React from 'react';

function MyComponent() {
  return (
    <>
      <h1>Title</h1>
      <p>Paragraph 1</p>
      <p>Paragraph 2</p>
    </>
  );
}

export default MyComponent;
```

<div id="q57"></div>

## 57. What are the benefits of using fragments ? [&uarr; Top](#top)
1. **Cleaner DOM Structure:** Fragments help keep your rendered DOM structure cleaner by avoiding unnecessary nesting of elements.

2. **No Extra Styles:** Wrapping elements in unnecessary parent elements can sometimes affect CSS and styling. Fragments don't introduce extra elements, so they don't interfere with styling.

3. **Improves Readability:** Fragments make your code more readable by allowing you to group elements together logically without introducing visual noise from extra parent elements.

4. **Performance:** While the impact is usually negligible, fewer DOM elements mean slightly improved rendering performance.

<div id="q58"></div>

## 58. Why fragments are better than container divs ? [&uarr; Top](#top)
Fragments and container `<div>` elements both serve a similar purpose of grouping multiple elements in React components. However, fragments offer several advantages over using container `<div>` elements:

1. **No Extra DOM Element:** The primary advantage of fragments is that they don't introduce an additional DOM element like `<div>` does. This means that using fragments reduces unnecessary nesting in the rendered output. Unnecessary nesting can impact both DOM structure and styling, especially when CSS rules are based on specific parent-child relationships.

2. **Cleaner DOM Structure:** When you use a `<div>` to wrap multiple elements, it introduces an extra layer of hierarchy in the DOM. Fragments, on the other hand, group elements together without adding any additional structure to the DOM, resulting in a cleaner, more efficient DOM structure.

3. **Avoid Styling Issues:** Wrapping elements in a `<div>` can sometimes affect CSS styling. Styles applied to the wrapping `<div>` can inadvertently affect the styling of its children. Fragments avoid this issue by not creating an additional element that participates in the styling hierarchy.

4. **Readability:** Fragments improve code readability by allowing you to group elements logically without introducing unnecessary visual noise from parent elements. This is especially beneficial when you have multiple levels of nesting.

5. **Performance:** While the performance impact is usually minimal, using fewer DOM elements can lead to slightly improved rendering performance, as there are fewer nodes to process and render.

Here's an example comparing the two approaches:

Using a `<div>` container:
```jsx
function UsingDiv() {
  return (
    <div>
      <h1>Title</h1>
      <p>Content</p>
    </div>
  );
}
```

Using a fragment:
```jsx
function UsingFragment() {
  return (
    <>
      <h1>Title</h1>
      <p>Content</p>
    </>
  );
}
```


<div id="q59"></div>

## 59. What are stateless components ? [&uarr; Top](#top)
Stateless components, also known as functional components, are a type of component in React that are defined as plain JavaScript functions and do not manage their own internal state using the useState hook or this.state. They receive data as props and render UI based on those props. Stateless components are primarily concerned with presenting data and do not have lifecycle method
```jsx
import React from 'react';

function Greeting(props) {
  return <h1>Hello, {props.name}!</h1>;
}

export default Greeting;
```

<div id="q6"></div>

## 6. ? [&uarr; Top](#top)






