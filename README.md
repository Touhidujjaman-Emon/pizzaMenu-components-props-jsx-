# Components , Props and JSX

## Components

![Components](<about components.png>)

### _2 important components as function rules in react_

- The first letter of a component name should be capitalized
- Function needs to retirn some markup(JSX) or null.

### Components tree

- A hierarchical structure of React components
- Each node represents a component, edges represent parent-child relationships
- Used by React to manage rendering and updating of components
- Example:

```jsx
<AppComponent>
  <Header />
  <MainContent>
    <Sidebar />
    <Article />
  </MainContent>
  <Footer />
</AppComponent>
```

Becomes:

```
AppComponent
  ├── Header
  ├── MainContent
  │   ├── Sidebar
  │   └── Article
  └── Footer
```

![components tree](<components tree.png>)

## JSX (JavaScript XML)

![JavaScript XML](JSX.png)

### JSX is declarative

- "declarative" refers to a programming paradigm where you describe what you want to see in your UI, rather than how to achieve it.

![declarative](JSX-declarative.png)
