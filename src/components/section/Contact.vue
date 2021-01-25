<template>
	<div id="contact">
                <h1 >CONTACT US</h1>
                <hr class="line-section" />
                <hr class="line-section" />
                <h5 >Please tell us about your next project and we will let you know what we can do to help you.</h5>
                <container>
                    <form class="contactus">
                        <formgroup>

                            <p><input class="form-input" type="text" placeholder="Name" /></p>
                            <p><input class="form-input" type="text" placeholder="Email Address" /></p>
                            <p><input class="form-input" type="text" placeholder="Phone Number" /></p>
                            <p><input class="form-input" type="textarea" placeholder="Message" /></p>
                            <button color="info" class="btn-send" block>Send
                        </button>
                        </formgroup>
                    </form>

                </container>
                <a href="#contact" class=" btn-block btn-full-width">Let's Discuss!</a>

            </div>
</template>
<style scoped>

@import "./style/contact.css";
@import "../style/App.css";
</style>