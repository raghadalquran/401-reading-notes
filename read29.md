## React Component Lifecycle Methods

![img](https://www.google.com/url?sa=i&url=https%3A%2F%2Fmedium.com%2F%40_ChrisBradshaw%2Fblogdidmount-2018-guide-to-react-component-lifecycle-methods-1614e0bbe80a&psig=AOvVaw11LO0r1smceQuaB5heR0MI&ust=1593591637571000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCNDgwc-NqeoCFQAAAAAdAAAAABAD)

## React’s props.children
My simple explanation of what this.props.children does is that it is used to display whatever you include between the opening and closing tags when invoking a component.

## Rendering a <Router>
Router components only expect to receive a single child element. To work within this limitation, it is useful to create an <App> component that renders the rest of your application. Separating your application from the router is also useful for server rendering because you can re-use the <App> on the server while switching the router to a <MemoryRouter>.

## Routes
The <Route> component is the main building block of React Router. Anywhere that you want to only render content based on the location’s pathname, you should use a <Route> element.

## Routing
Using react-router, you can easily toggle the visibility of components (or even pages) based on the URL/Route that the user engages with.
import { Route } from 'react-router-dom';
To use Browser Router properly, you eliminate your use of <a> tags and instead use it’s built-in <Link> component.
