## rrc
#### reactReduxComponent
Creates a React component class connected to redux
```
import React, { Component } from 'react';
import { connect } from 'react-redux';

function mapStateToProps(state) {
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