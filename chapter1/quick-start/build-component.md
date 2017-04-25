# Build Component

#### Here at WalmartLabs we love to build!

After you've generated your awesome electrode app, you are ready to focus on writing your React components.

Navigate to`<your-awesome-app>/src/client/components/home.jsx`:

```
import React, {PropTypes} from "react";
import {connect} from "react-redux";
import {toggleCheck, incNumber, decNumber} from "../actions";

class Home extends React.Component {
  render() {
    const props = this.props;
    const {checked, value} = props;
    return (
      <div>
        <h1>Hello <a href={"https://github.com/electrode-io"}>{"Electrode"}</a></h1>
        <div>
          <h2>Managing States with Redux</h2>
          <label>
            <input onChange={props.onChangeCheck} type={"checkbox"} checked={checked}/>
            Checkbox
          </label>
          <div>
            <button type={"button"} onClick={props.onDecrease}>-</button>
            &nbsp;{value}&nbsp;
            <button type={"button"} onClick={props.onIncrease}>+</button>
          </div>
        </div>
      </div>
    );
  }
}

Home.propTypes = {
  checked: PropTypes.bool,
  value: PropTypes.number.isRequired
};

const mapStateToProps = (state) => {
  return {
    checked: state.checkBox.checked, value: state.number.value
  };
};

const mapDispatchToProps = (dispatch) => {
  return {
    onChangeCheck: () => {
      dispatch(toggleCheck());
    },
    onIncrease: () => {
      dispatch(incNumber());
    },
    onDecrease: () => {
      dispatch(decNumber());
    }
  };
};

export default connect(mapStateToProps, mapDispatchToProps)(Home);
```

We'll need a place to keep all of the resources we learned in the [Get Started](http://www.electrode.io/docs/get_started.html) section. Let's make a visual library for our present stack and exciting technologies! Copy the code below and paste it into 

`<your-awesome-app> /src/client/components/home.jsx`:



