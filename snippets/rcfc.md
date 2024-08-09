## rcfc
#### reactClassComponentWithMethods
Creates a React component class with PropTypes and all lifecycle methods and ES6 module system
```
import React, { Component } from 'react';
import PropTypes from 'prop-types';

class ${1:${TM_FILENAME_BASE}} extends Component {
	constructor(props) {
		super(props);
		this.state = {
			
		}
	}

	static getDerivedStateFromProps() {
		return null
	}

	componentDidMount() {
		
	}

	// shouldComponentUpdate(nextProps, nextState) {}

	getSnapshotBeforeUpdate(prevProps, prevState) {
		return null
	}

	componentDidUpdate(prevProps, prevState, snapshot) {
		
	}

	componentWillUnmount() {
		
	}

	render() {
		return (
			<div>
				
			</div>
		);
	}
}

${1:${TM_FILENAME_BASE}}.propTypes = {
	
};

export default ${1:${TM_FILENAME_BASE}};
```