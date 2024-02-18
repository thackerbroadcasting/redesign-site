---
layout: page
title: Data Subject Access Request Form
show_sidebar: false
hero_height: none
---
<style>
.div-class {
    margin-top:3rem;
}

.input {
    box-shadow: 2px 2px;
}

.input-radio {

}

.input-dropdown {

}

.button {
    border-radius: 0.5rem
}
</style>

<h3>Got a technical issue? Want to send feedback about a beta feature? Need details about our Business plan? Let us know.</h3>
<section>
    <div>
        <form action="https://formspree.io/f/mpzvqdqp" method="POST">
            <div class="div-class">
          	    <label for="name"><strong>Full Name:</strong></label><br>
            	    <input class="input" type="message" name="name" placeholder="First Last" required>
            </div>
            <div class="div-class">
                <label for="email"><strong>Your Email:</strong></label><br>
                    <input class="input" type="email" name="email" placeholder="name@example.com" required>
            </div>
            <div class="div-class">
          	    <label for="submitting-for"><strong>You are submitting this request as:</strong></label><br>
                    <input type="radio" name="submitting-for" value="The person, or the parent/guardian of the person, whose name appears above." required>
                        <label for="myself">The person, or the parent/guardian of the person, whose name appears above.</label><br>
                    <input type="radio" name="submitting-for" value="An agent authorized by the consumer to make this request on their behalf.">
                        <label for="someone-else">An agent authorized by the consumer to make this request on their behalf.</label><br>
            </div>
            <div class="div-class">
          	    <label for="rights"><strong>Under the rights of which law are you making this request?</strong></label><br>
                    <select class="input" name="rights" required>
                        <option value="ccpa">CCPA</option>
                        <option value="gdpr">GDPR</option>
                    </select>
            </div>
            <div class="div-class">
                <label for="reason-for-request"><strong>I am submitting a request to ______</strong></label><br>
                    <input type="radio" name="reason-for-request" value="Know what information is being collected from me" required>
                        <label for="what-is-collected">Know what information is being collected from me</label><br>
                    <input type="radio" name="reason-for-request" value="Have my information deleted">
                        <label for="what-is-collected">Have my information deleted</label><br>
                    <input type="radio" name="reason-for-request" value="Opt out of having data sold to third parties">
                        <label for="what-is-collected">Opt out of having data sold to third parties</label><br>
                    <input type="radio" name="reason-for-request" value="Opt in to the sale of my personal data">
                        <label for="what-is-collected">Opt in to the sale of my personal data</label><br>
            </div>
            <div class="div-class">
                <label for="request-details"><strong>Please leave details regarding your action request or question.</strong></label><br>
                    <textarea class="input" name="request-details" rows="6" placeholder="Request details..." required></textarea>
            </div>
            <div class="div-class">
                <label for="confirmation"><strong>I confirm that...</strong></label><br>
                    <input type="checkbox" name="confirmation" value="Under penalty of perjury, I declare all the above information to be true and accurate." required>
                        <label for="confirmation">Under penalty of perjury, I declare all the above information to be true and accurate.</label><br>
                    <input type="checkbox" name="confirmation" value="I under that the deletion or restriction of my personal data is irreversible and may result in the termination of services with Thacker Broadcasting." required>
                        <label for="confirmation">I under that the deletion or restriction of my personal data is irreversible and may result in the termination of services with Thacker Broadcasting.</label><br>
                    <input type="checkbox" name="confirmation" value="I understand that I will be required to validate my request by email, and I may be contacted in order to complete the request." required>
                        <label for="confirmation">I understand that I will be required to validate my request by email, and I may be contacted in order to complete the request.</label><br>
            </div>
            <div class="div-class">
                <button class="button" type="submit">Submit Request</button>
            </div>
        </form>
    </div>
</section>