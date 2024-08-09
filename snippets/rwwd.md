## rwwd
#### reactWithWebpackDefaults
Creates a React component class with constructor, empty state, proptypes and export in ES6 module system without imports. (Mostly used when React, Proptypes are provided by webpack provide plugin)
```
class ${1:${TM_FILENAME_BASE}} extends React.Component {
	constructor(props) {
		super(props);

		this.state = {};

	}

	render() {
		return (
			<div>
				$0
			</div>
		);
	}
}

${1:${TM_FILENAME_BASE}}.propTypes = {

};

export default ${1:${TM_FILENAME_BASE}};
```