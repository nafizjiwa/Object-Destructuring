# Object-Destructuring

Destructure an object of properties passed down or between files and how to extract them from the object literal

...object destructuring syntax…

      const { propA, propB } = props;

...plain object dot notation…

      const propA = props.propA;
      const propB = props.propB;

...or directly pull them out of the parameter list

      const MyComponent = ({propA, propB}) => { // Component code or  }

#### Parameters and properties are extracted to use in a feature or functional components which are passed down from top level components.


