## rrdc
#### reactReduxDispatchComponent
Creates a React component class connected to redux with dispatch
```
import React, { Component } from 'react';
import { connect } from 'react-redux';

function mapStateToProps(state) {
	return {

	};
}

function mapDispatchToProps(dispatch) {
	return {

	};
}

class ${1:${TM_FILENAME_BASE}} extends Component {
	render() {
		return (
			<div>
				$0
			</div>
		);
	}
}

export default connect(
	mapStateToProps,
)(${1:${TM_FILENAME_BASE}});
```