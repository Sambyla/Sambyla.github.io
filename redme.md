# portfolio
                        <!-- * * * * * * * * * * * * * * *-->
                        <!-- * * SB Forms Contact Form * *-->
                        <!-- * * * * * * * * * * * * * * *-->
                        <!-- This form is pre-integrated with SB Forms.-->
                        <!-- To make this form functional, sign up at-->
                        <!-- https://startbootstrap.com/solution/contact-forms-->
                        <!-- to get an API token!-->
        <!---->                <form id="contactForm" data-sb-form-api-token="API_TOKEN">
        <!---->                    <!-- Name input-->
        <!---->                    <div class="form-floating mb-3">
        <!---->                        <input class="form-control" id="name" type="text" placeholder="Enter your name..." data-sb-validations="required" />
        <!---->                        <label for="name">Koko nimi</label>
        <!---->                        <div class="invalid-feedback" data-sb-feedback="name:required">Nimi tarvitaan.</div>
        <!---->                    </div>
        <!---->                    <!-- Email address input-->
        <!---->                    <div class="form-floating mb-3">
        <!---->                        <input class="form-control" id="email" type="email" placeholder="name@example.com" data-sb-validations="required,email" />
        <!---->                        <label for="email">Email</label>
        <!---->                        <div class="invalid-feedback" data-sb-feedback="email:required">Email tarvitaan.</div>
        <!---->                        <div class="invalid-feedback" data-sb-feedback="email:email">Email ei ole oikein.</div>
        <!---->                    </div>
        <!---->                    <!-- Phone number input-->
        <!---->                    <div class="form-floating mb-3">
        <!---->                        <input class="form-control" id="phone" type="tel" placeholder="(123) 456-7890" data-sb-validations="required" />
        <!---->                        <label for="phone">Puhelin numero</label>
        <!---->                        <div class="invalid-feedback" data-sb-feedback="phone:required">puhelin numero tarvitaan.</div>
        <!---->                    </div>
        <!---->                    <!-- Message input-->
        <!---->                    <div class="form-floating mb-3">
        <!---->                        <textarea class="form-control" id="message" type="text" placeholder="Enter your message here..." style="height: 10rem" data-sb-validations="required"></textarea>
        <!---->                        <label for="message">Viestisi</label>
        <!---->                        <div class="invalid-feedback" data-sb-feedback="message:required">Viestisi tarvitaan.</div>
        <!---->                    </div>
                            <!-- Submit success message-->
                            <!---->
                            <!-- This is what your users will see when the form-->
                            <!-- has successfully submitted-->
                            <div class="d-none" id="submitSuccessMessage">
                                <div class="text-center mb-3">
                                    <div class="fw-bolder">Lähetys onnistui!</div>
                                    Aktivoidaksesi lomakkeen sinun on kirjauduttava täältä
                                    <br />
                                    <a href="https://startbootstrap.com/solution/contact-forms">https://startbootstrap.com/solution/contact-forms</a>
                                </div>
                            </div>
                            <!-- Submit error message-->
                            <!---->
                            <!-- This is what your users will see when there is-->
                            <!-- an error submitting the form-->
                            <div class="d-none" id="submitErrorMessage"><div class="text-center text-danger mb-3">Jokin meni pieleen!</div></div>
                            <!-- Submit Button-->
                            <button class="btn btn-primary btn-xl disabled" id="submitButton" type="submit">Lähetä</button>
                        </form>