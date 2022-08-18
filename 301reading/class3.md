constructor(props){
    super(props);
    this.state = {
        heart: ''
    }
}
adds state that can be inherited to lower components.  
handleHeart = () => {
    this.setState({
        hearts:this.state.heart + true
    })
}
changes the state of the heart prop
<Person 
name={pep.name}
handleHeart={this.props.handleHeart}>
Brings the function down to the componenet

Modal are alert windows that stay withing the window.

Import modal from React  
constructor(props){
    super(props);
    this.state = {
        heart: ''
        showModal: true
    }
}
<Modal show={this.state.showModal}><Modal/>
add a value to state.  
Add methods to state
handleShowModal = () => {
    this.setState({
        showModal: true
    })
}
handleHideModal = () => {
    this.setState({
        showModal: false
    })
}
This will be used to show or hie the modal.  
<Modal onHide= {this.handleHideModal}></Modal>