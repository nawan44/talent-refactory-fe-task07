<template>
	<div id="contact">
                <h1 >CONTACT US</h1>
                <hr className="line-section" />
                <hr className="line-section" />
                <h5 >Please tell us about your next project and we will let you know what we can do to help you.</h5>
                <Container>
                    <Form className="contactus">
                        <FormGroup>

                            <p><Input className="FormInput" type="text" placeholder="Name" /></p>
                            <p><Input className="FormInput" type="text" placeholder="Email Address" /></p>
                            <p><Input className="FormInput" type="text" placeholder="Phone Number" /></p>
                            <p><Input className="FormInput" type="textarea" placeholder="Message" /></p>
                            <Button color="info" className="btn-send" block>Send
                        </Button>
                        </FormGroup>
                    </Form>

                </Container>
                <a href="#contact" class="btn btn-block btn-full-width">Let's Discuss!</a>

            </div>
</template>