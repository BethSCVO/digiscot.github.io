---
layout: page
title: Sign the Charter
excerpt: Here's your chance to help promote digital participation in Scotland.
permalink: /charter/sign/
---

<script src="http://cdn.jsdelivr.net/jquery.validation/1.13.1/jquery.validate.min.js" type="text/javascript"></script>
<script src="http://ajax.aspnetcdn.com/ajax/mvc/5.2/jquery.validate.unobtrusive.min.js" type="text/javascript"></script>
<script src="http://malsup.github.com/jquery.form.js"></script>

<form action="http://scvoapi.azurewebsites.net/Charter/Sign" id="frmManagedigitalContacts" method="POST">

    <input name="__RequestVerificationToken" type="hidden" 
        value="p2B1TwWKaIND707fr4Q5Ynp0W7JT0UaTNE2BIU_lKVhhio4xUi6G-j-jBPufq6JBqMQ8ANbOSx1ElRZ8y3rdoiTtCEMGZAKDFmEl_Ev6asQ1" />
    <div class="container">
        <div class="row-fluid">
            <div class="col-md-12" style="padding-right:15px;">
                <div class="content-widgets light-gray">
                    <div class="widget-container">
                        <div id="chatter-form">
                            <div class="form-group">
                                <input data-val="true" data-val-number="The field Please tell us which of the following resources or practical support your organisation might be interested in offering as a Charter signatory: must be a number." id="PracticalSupportId" name="PracticalSupportId" type="hidden" value="" />

                                <div id="result" class="result"></div>
                            </div>
                            <div class="panel1 panel-primary">
                                <div class="panel-body form-group">
                                    <div class="col-lg-12">
                                    
                                        <div class="row form-group">

                                            <div class="col-md-6 form-group">
                                                <label> <label for="FirstName">First Name</label></label>
                                                <input class="form-control" data-val="true" data-val-required="The First Name field is required." id="FirstName" name="FirstName" type="text" value="" />
                                                <span class="field-validation-valid text-danger" data-valmsg-for="FirstName" data-valmsg-replace="true"></span>
                                            </div>
                                            <div class="col-md-6 form-group">

                                                <label> <label for="LastName">Last Name</label></label>
                                                <input class="form-control" data-val="true" data-val-required="The Last Name field is required." id="LastName" name="LastName" type="text" value="" />
                                                <span class="field-validation-valid text-danger" data-valmsg-for="LastName" data-valmsg-replace="true"></span>
                                            </div>

                                        </div>

                                        <div class="row form-group">

                                            <div class="col-md-8 form-group">
                                                <label> <label for="OrganisationName">Please tell us the name of your organisation</label></label>
                                                <input class="form-control" id="OrganisationName" name="OrganisationName" type="text" value="" />
                                                <span class="field-validation-valid text-danger" data-valmsg-for="OrganisationName" data-valmsg-replace="true"></span>
                                            </div>
                                            <div class="col-md-4 form-group">
                                                <label> <label for="Position">Position Within Organisation</label></label>
                                                <input class="form-control" id="Position" name="Position" type="text" value="" />
                                                <span class="field-validation-valid text-danger" data-valmsg-for="Position" data-valmsg-replace="true"></span>
                                            </div>

                                        </div>

                                        <div class="form-group">
                                            <label for="Email">Email Address</label>
                                            <input class="form-control" data-val="true" data-val-regex="Email is not valid" data-val-regex-pattern="^([a-zA-Z0-9_\-\.]+)@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.)|(([a-zA-Z0-9\-]+\.)+))([a-zA-Z]{2,4}|[0-9]{1,3})(\]?)$" data-val-required="The Email Address field is required." id="Email" name="Email" type="text" value="" />
                                            <span class="field-validation-valid text-danger" data-valmsg-for="Email" data-valmsg-replace="true"></span>
                                        </div>

                                        <div class="form-group">
                                            <label for="Phone">Telephone Number</label>
                                            <input class="form-control" id="Phone" name="Phone" type="text" value="" />
                                            <span class="field-validation-valid text-danger" data-valmsg-for="Phone" data-valmsg-replace="true"></span>
                                        </div>

                                        <div class="form-group">
                                            <label for="Address1">Address line 1</label>
                                            <input class="form-control" data-val="true" data-val-required="The Address line 1 field is required." id="Address1" name="Address1" type="text" value="" />
                                            <span class="field-validation-valid text-danger" data-valmsg-for="Address1" data-valmsg-replace="true"></span>
                                        </div>

                                        <div class="form-group">
                                            <label for="Address2">Address line 2</label>
                                            <input class="form-control" data-val="true" data-val-required="The Address line 2 field is required." id="Address2" name="Address2" type="text" value="" />
                                            <span class="field-validation-valid text-danger" data-valmsg-for="Address2" data-valmsg-replace="true"></span>
                                        </div>

                                        <div class="form-group">
                                            <label for="Address3">Address line 3</label>

                                            <input class="form-control" id="Address3" name="Address3" type="text" value="" />
                                            <span class="field-validation-valid text-danger" data-valmsg-for="Address3" data-valmsg-replace="true"></span>

                                        </div>

                                        <div class="form-group">
                                            <label for="PostCode">Postcode</label>

                                            <input class="form-control" data-val="true" data-val-required="The Postcode field is required." id="PostCode" name="PostCode" type="text" value="" />
                                            <span class="field-validation-valid text-danger" data-valmsg-for="PostCode" data-valmsg-replace="true"></span>

                                        </div>

                                        <div class="form-group">
                                            <label for="PaidEmployeesId">Please tell us how many paid employees you have within your organisation's workforce, that work solely or mainly in Scotland.</label>
                                            <select class="form-control " id="PaidEmployeesId" name="PaidEmployeesId"><option value="">Please select</option>
                                                <option value="1">None</option>
                                                <option value="2">1 to 4</option>
                                                <option value="3">5 to 9 </option>
                                                <option value="4">10 to 19</option>
                                                <option value="5">20 to 49</option>
                                                <option value="6">50 to 99</option>
                                                <option value="7">100 to 249</option>
                                                <option value="8">250 to 499</option>
                                                <option value="9">500 to 999</option>
                                                <option value="10">1,000+</option>
                                            </select>
                                            <span class="field-validation-valid text-danger" data-valmsg-for="PaidEmployeesId" data-valmsg-replace="true"></span>
                                        </div>

                                        <div class="form-group">
                                            <label> <label for="ActiveVolunteersId">Please tell us how many volunteers are part of your organisation's workforce, that are active solely or mainly in Scotland.</label></label>

                                            <select class="form-control " id="ActiveVolunteersId" name="ActiveVolunteersId"><option value="">Please select</option>
                                                <option value="1">None</option>
                                                <option value="2">1 to 4</option>
                                                <option value="3">5 to 9 </option>
                                                <option value="4">10 to 19</option>
                                                <option value="5">20 to 49</option>
                                                <option value="6">50 to 99</option>
                                                <option value="7">100 to 249</option>
                                                <option value="8">250 to 499</option>
                                                <option value="9">500 to 999</option>
                                                <option value="10">1,000+</option>
                                                <option value="11">None, we don&#39;t engage volunteers</option>
                                            </select>
                                            <span class="field-validation-valid text-danger" data-valmsg-for="ActiveVolunteersId" data-valmsg-replace="true"></span>

                                        </div>

                                        <div class="form-group">
                                            <label for="GeographicalId">Please indicate which of the following best describes your organisation's geographical reach across Scotland.</label>
                                            <select class="form-control " id="GeographicalId" name="GeographicalId"><option value="">Please select</option>
                                                <option value="1">Scotland Wide</option>
                                                <option value="2">Across multiple local authorities</option>
                                                <option value="3">Across one local authority</option>
                                                <option value="4">Particular neighbourhoods within one of more local authorities</option>
                                            </select>
                                            <span class="field-validation-valid text-danger" data-valmsg-for="GeographicalId" data-valmsg-replace="true"></span>
                                        </div>
                                        <div class="form-group" id="authority-details" style="display:none;">

                                            <label>Please Specify:</label>
                                            <textarea cols="20" id="LocalAuthorityString" name="LocalAuthorityString" rows="5" class="form-control"></textarea>

                                        </div>
                                        <div class="form-group">
                                            <label for="SectorId">What sector do you consider your organisation to be part of:</label>
                                            <select class="form-control " id="SectorId" name="SectorId"><option value="">Please select</option>
                                                <option value="1">Public Sector</option>
                                                <option value="2">Private Sector</option>
                                                <option value="3">Third Sector</option>
                                                <option value="4">Other</option>
                                            </select>
                                            <span class="field-validation-valid text-danger" data-valmsg-for="SectorId" data-valmsg-replace="true"></span>

                                            <div class="r">
                                                <hr class="divider" />
                                                <div class="c s--full m--two-thirds">
                                                    <label style="display:none;" id="sector-match-label">What is your main area of work?</label>
                                                    <!-- if Q1 == Public -->
                                                    <div id="public-sector" style="display:none">
                                                        <select class="form-control" id="PublicSector" name="PublicSector">
                                                            <option value="default">Please select</option>
                                                            <option value="Local Government">Local Government</option>
                                                            <option value="National Government">National Government</option>
                                                            <option value="Health">Health</option>
                                                            <option value="Policy Authority">Policy Authority</option>
                                                            <option value="Fire Service">Fire Service</option>
                                                            <option value="Education">Education</option>
                                                            <option value="Other">Other</option>
                                                        </select>
                                                    </div>
                                                    <!-- if Q1 == Private -->
                                                    <div id="private-sector" style="display:none;">
                                                        <select class="form-control" id="PrivateSector" name="PrivateSector">
                                                            <option value="default">Please select</option>
                                                            <option value="Service Industries">Service Industries</option>
                                                            <option value="Science and Technology">Science and Technology</option>
                                                            <option value="Information / Communications / Media">Information / Communications / Media</option>
                                                            <option value="Travel and Leisure">Travel and Leisure</option>
                                                            <option value="Business and Finance">Business and Finance</option>
                                                            <option value="Education">Education</option>
                                                            <option value="Wholesale and Retail">Wholesale and Retail</option>
                                                            <option value="Hospitality and Catering">Hospitality and Catering</option>
                                                            <option value="Utilities">Utilities</option>
                                                            <option value="Construction">Construction</option>
                                                            <option value="Agriculture">Agriculture</option>
                                                            <option value="Transport and Distribution">Transport and Distribution</option>
                                                            <option value="Health">Health</option>
                                                            <option value="Mining">Mining</option>
                                                            <option value="Real Estate">Real Estate</option>
                                                            <option value="Other">Other</option>
                                                        </select>
                                                    </div>
                                                    <!-- if Q1 == Third -->
                                                    <div id="third-sector" style="display:none">
                                                        <select class="form-control" id="ThirdSector" name="ThirdSector">
                                                            <option value="default">Please select</option>
                                                            <option value="Community, Social or Economic Development">Community, Social or Economic Development</option>
                                                            <option value="Culture and Recreation">Culture and Recreation</option>
                                                            <option value="Education and Research">Education and Research</option>
                                                            <option value="Environment and Animals">Environment and Animals</option>
                                                            <option value="Faith Related">Faith Related</option>
                                                            <option value="General Purposes">General Purposes</option>
                                                            <option value="Health">Health</option>
                                                            <option value="Housing">Housing</option>
                                                            <option value="Law, Advocacy, Politics">Law, Advocacy, Politics</option>
                                                            <option value="Social Care">Social Care</option>
                                                            <option value="Other">Other</option>
                                                        </select>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>


                                        <fieldset>
                                            <h3>Basic Digital Skills & Your Workforce </h3>
                                            <hr/>
                                        </fieldset>
                                        <div >
                                            <p>
                                                We would like to understand more about the level of basic digital  skills across Scotland's workforce.
                                            </p>
                                            <p>

                                                These are the basic digital skills that people and organisations need to get things done online.
                                            </p>
                                            <p>	We have adopted the basic digital skills definition developed by Go ON UK. Find out more at <a href="http://digital.scvo.org.uk/basic-digital-skills">http://digital.scvo.org.uk/basic-digital-skills</a> </p>
                                            <div class="table-wrap">

                                                <table class="table table-bordered table-striped">

                                                    <thead>

                                                        <tr>

                                                            <td colspan="4">Basic digital skills for individuals</td>

                                                        </tr>

                                                    </thead>

                                                    <tbody>

                                                       

                                                        <tr>

                                                            <td class="pink">Keeping safe online</td>
                                                            <td>Identify and delete spam</td>
                                                            <td>Evaluate which websites to trust</td>
                                                            <td>
                                                                Evaluate which websites to trust<br>
                                                                Set privacy settings
                                                            </td>

                                                        </tr>

                                                    </tbody>

                                                </table>

                                            </div>

                                            <div id="paid-employee-info" style="display:none;" class="form-group">
                                                <hr class="divider">

                                                
                                                <label for="DigitalLiteracyScale">What percentage of paid employees within your organisation's workforce do you estimate to have the basic digital skills outlined above?</label>
                                                <select id="DigitalLiteracyScale" name="DigitalLiteracyScale" class="form-control">
                                                    <option value="default">Please select</option>
                                                    <option value="100% of staff">100% of paid employees</option>
                                                    <option value="At least 75% of staff">At least 75% of paid employees</option>
                                                    <option value="At least 50% of staff">At least 50% of paid employees</option>
                                                    <option value="At least 25% of staff">At least 25% of paid employees</option>
                                                    <option value="Less than 25% of staff">Less than 25% of paid employees</option>
                                                    <option value="Don't know">Don't know</option>
                                                </select>

                                            </div>

                                            <div id="volunteer-info" style="display:none;" class="form-group">
                                                <hr class="divider" />
                                                
                                                <label for="VolunteerDigitalLiteracyScale">What percentage of volunteers within your organisation's workforce do you estimate to have the basic digital skills outlined above?</label>
                                                <select id="VolunteerDigitalLiteracyScale" name="VolunteerDigitalLiteracyScale" class="form-control">
                                                    <option value="default">Please select</option>
                                                    <option value="100% of volunteers">100% of volunteers</option>
                                                    <option value="At least 75% of volunteers">At least 75% of volunteers</option>
                                                    <option value="At least 50% of volunteers">At least 50% of volunteers</option>
                                                    <option value="At least 25% of volunteers">At least 25% of volunteers</option>
                                                    <option value="Less than 25% of volunteers">Less than 25% of volunteers</option>
                                                    <option value="Don't know">Don't know</option>
                                                </select>

                                            </div>

                                        </div>
                                        
                                        <fieldset>
                                            <h3>Supporting Digital Participation</h3>
                                            <hr />
                                        </fieldset>
                                        <div class=" form-group">
                                            <p>As part of the Digital Participation Charter we ask that signatories offer resources & / or practical support to digital participation activities that will help others to gain basic digital skills. We are therefore interested in finding out what your organisation already does and what else you would like to be able to offer.</p>
                                            <div class="form-group">
                                                <label for="PeopleSupport">What, if anything, are you already doing to support people (outside your organisation) to gain basic online skills?</label>

                                                <textarea class="form-control" cols="25" data-val="true" data-val-required="The What, if anything, are you already doing to support people (outside your organisation) to gain basic online skills? field is required." id="PeopleSupport" name="PeopleSupport" rows="5"> </textarea>
                                                <span class="field-validation-valid text-danger" data-valmsg-for="PeopleSupport" data-valmsg-replace="true"></span>

                                            </div>

                                            <div class="form-group">
                                                <label> <label for="PracticalSupportId">Please tell us which of the following resources or practical support your organisation might be interested in offering as a Charter signatory:</label></label>
                                                <div class="checkbox col-md-3 col-xs-6">
                                                    <label class="col">
                                                        <input name="PracticalSupport[]" id="Act_Provision" type="checkbox" value="Provision of IT equipment">
                                                        <i></i> Provision of IT equipment
                                                    </label>
                                                </div>
                                                <div class="checkbox col-md-3 col-xs-6">
                                                    <label class="col">
                                                        <input name="practicalSupport[]" id="Act_Repair" type="checkbox" value="Repair or adaptation of IT equipment">
                                                        <i></i> Repair or adaptation of IT equipment
                                                    </label>
                                                </div>
                                                <div class="checkbox col-md-3 col-xs-6">
                                                    <label class="col">
                                                        <input name="PracticalSupport[]" id="Act_Infrastructure" type="checkbox" value="Infrastructure support / advice ">
                                                        <i></i> Infrastructure support / advice
                                                    </label>
                                                </div>
                                                <div class="checkbox col-md-3 col-xs-6">
                                                    <label class="col">
                                                        <input name="PracticalSupport[]" id="Act_Web" type="checkbox" value="Web / social media support / advice">
                                                        <i></i> Web / social media support / advice
                                                    </label>
                                                </div>
                                                <div class="checkbox col-md-3 col-xs-6">
                                                    <label class="col">
                                                        <input name="PracticalSupport[]" id="Act_Provision" type="checkbox" value="Provision of venues">
                                                        <i></i> Provision of venues
                                                    </label>
                                                </div>
                                                <div class="checkbox col-md-3 col-xs-6">
                                                    <label class="col">
                                                        <input name="PracticalSupport[]" id="Act_IT related consultancy" type="checkbox" value="IT related consultancy">
                                                        <i></i> IT related consultancy
                                                    </label>
                                                </div>
                                                <div class="checkbox col-md-3 col-xs-6">
                                                    <label class="col">
                                                        <input name="PracticalSupport[]" id="Act_Staff release" type="checkbox" value="Staff release">
                                                        <i></i> Staff release
                                                    </label>
                                                </div>
                                                <div class="checkbox col-md-3 col-xs-6">
                                                    <label class="col">
                                                        <input name="PracticalSupport[]" id="Act_Signposting / marketing in public areas" type="checkbox" value="Signposting / marketing in public areas">
                                                        <i></i> Signposting / marketing in public areas
                                                    </label>
                                                </div>
                                                <div class="checkbox col-md-3 col-xs-6">
                                                    <label class="col">
                                                        <input name="PracticalSupport[]" id="Act_Marketing / communications materials" type="checkbox" value="Marketing / communications materials">
                                                        <i></i> Marketing / communications materials
                                                    </label>
                                                </div>
                                                <div class="checkbox col-md-3 col-xs-6">
                                                    <label class="col">
                                                        <input name="PracticalSupport[]" id="Act_Money" type="checkbox" value="Money">
                                                        <i></i> Money
                                                    </label>
                                                </div>
                                                <div class="checkbox col-md-3 col-xs-6">
                                                    <label class="col">
                                                        <input name="PracticalSupport[]" id="Act_None" type="checkbox" value="None">
                                                        <i></i> None
                                                    </label>
                                                </div>

                                                <span class="field-validation-valid text-danger" data-valmsg-for="PracticalSupportId" data-valmsg-replace="true"></span>

                                            </div>

                                            <div class="form-group">
                                                <label>  This list above is not exhaustive and is just a starting point for ideas. We are keen for Charter signatories to draw on their organisations expertise and identify their own offers for development.</label>
                                            </div>
                                            <div class="form-group">
                                                <label><label for="PotentialOffers">Please tell us about any other ideas or potential offers that your organisation might be interested in developing as a Charter signatory:</label></label><br /><br />

                                                <textarea class="form-control" cols="25" data-val="true" data-val-required="The Please tell us about any other ideas or potential offers that your organisation might be interested in developing as a Charter signatory: field is required." id="PotentialOffers" name="PotentialOffers" rows="5"></textarea>
                                                <span class="field-validation-valid text-danger" data-valmsg-for="PotentialOffers" data-valmsg-replace="true"></span>

                                            </div>

                                            <div class="form-group">
                                                <label>
                                                    <label for="OrganisationAssistance">Please tell us if there is anything that would be of assistance to your organisation in developing potential offers:</label>
                                                </label><br /><br />
                                                <textarea class="form-control" cols="25" id="OrganisationAssistance" name="OrganisationAssistance" rows="5"></textarea>
                                                <span class="field-validation-valid text-danger" data-valmsg-for="OrganisationAssistance" data-valmsg-replace="true"></span>

                                            </div>

                                        </div>
                                        
                                        <div class="form-group" id="logoFileBox">
                                            <b>Please include a logo of your organisation:</b><br />
                                            <input type="file" class="btn btn-lg btn-info" id="logoFile" onchange="logoFileChanged()" name="logoFile" accept="image/*">
                                            <span class="text-danger field-validation-error" id="logoFileValidationError" style="display:none;">
                                                <span id="LogoFile-error" class="">
                                                    Please include an image file (max 4 MB)
                                                </span>
                                            </span>
                                        </div>

                                        <div class="form-group">
                                            <div class="controls">
                                                <button type="submit" class="btn btn-primary btn-lg" id="btnSearch">Pledge your Support </button>
                                                <!--<input type="button" id="btnSubmit" onclick="submit(event)" class="btn btn-primary btn-lg" value="Pledge your Support" />-->
                                                
                                                <span id="divProcessing" class="alert ">Processing, please wait . . . 
                                                    <img src="http://www.geniosity.co.za/genwp/wp-content/uploads/2007/01/ajax-loader-animated-2.gif" alt="ajax-loader">
                                                </span> <span id="result" class="result"> </span>
                                            </div>
                                                
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="form-group" id="finalSub">						
                        <p >Thank you for signing up to Scotland's Digital Participation Charter. We will be in touch with you soon to discuss ways you can actively support this national movement.</p>
                        <p><a class="btn btn-primary btn-lg"  href="javascript:self.close();" title="Close">Close</a></p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</form>


<script type="text/javascript">

    function logoFileChanged() {
        $("#logoFileValidationError").hide();
    }

    function validate() {
        $("#divProcessing").show();
        var message = "";
        //if ($("#RoleName").val() == '') {
        //    message += "Job title is required\n";
        //}

        //if ($("#SectorId").val() == '') {
        //    message += "Sector is required\n";
        //}

        if (message != "") {
            $("#divProcessing").hide();
            alert(message);
           // OnErrorCall(message);
            return false;
        }

        return false;
    }
    $(document).ready(function () {

        //$("[id$='OrganisationAssistance']").limit_textarea({ maxLength: 500, displayTextPosition: 'bottomleft' });
        //$("[id$='PotentialOffers']").limit_textarea({ maxLength: 500, displayTextPosition: 'bottomleft' });

        //$("[id$='OrganisationAssistance']").limit_textarea({ maxLength: 500, displayText: ' THIS QUESTION HAS A 500 WORD LIMIT' });
        //$("[id$='PotentialOffers']").limit_textarea({ maxLength: 500, displayText: '' });
        //$("[id$='txtArea4']").limit_textarea({ displayTextPosition: 'bottomright' });
        //$("[id$='txtArea5']").limit_textarea({ displayText: ' more chracters to go.' });
        //$("[id$='txtArea6']").limit_textarea({ maxLength: 125 });
    });

    $(document).ready(function () {
        // Hide the "busy" Gif at load:
        $("#divProcessing").hide();
        $("#finalSub").hide();
    });
    
    // prepare the form when the DOM is ready
    $(document).ready(function () {
        var options = {
            // target: '#output2',   // target element(s) to be updated with server response
            beforeSubmit: function() {
                $('#divProcessing').show();
            },
            //success: validate(),  // post-submit callback
            success: function (response) {
                //console.log(response);
                if (response === '') {
                    OnSuccessCall();
                } else {
                    OnErrorCall('Problems reported while saving your data:  ' + response);
                }
                $('#divProcessing').hide();

            },
            error: function (response) {
                OnErrorCall('Technical error');
                $('#divProcessing').hide();
            },
            url: this.action,
            type: this.method
        };


        // bind to the form's submit event
        $('#frmManagedigitalContacts').submit(function () {
            // inside event callbacks 'this' is the DOM element so we first
            // wrap it in a jQuery object and then invoke ajaxSubmit
            $(this).ajaxSubmit(options);

            // !!! Important !!!
            // always return false to prevent standard browser submit and page navigation
            return false;
        });

    });

    function OnSuccessCall() {
        window.location.href = 'http://digital.scvo.org.uk/charter/ok/';
    }

    function OnErrorCall(error) {
        if (!$("#logoFile").val()) {
            $("#logoFileValidationError").show();
        }
        $(".result").html('<div class="alert alert-danger"><button type="button" class="close">&times;</button>  <br />' + error + '</div>');
        window.setTimeout(function () {
            $(".alert").fadeTo(500, 0).slideUp(500, function () {
                //$(this).remove();
            });
        }, 5000);
        $('.alert .close').on("click", function (e) {
            $(this).parent().fadeTo(500, 0).slideUp(500);
        });
    }

    // post-submit callback
    function showRequest() {
        $("#divProcessing").show();
    }

    $(function () {
        $('#SectorId').change(function () {
            var $el = $(this).find(':selected');
            var sector = $el.attr('value');
            if (sector != "default") {
                $('#sector-match-label').show();
                switch (sector) {
                    case "1":
                        $('#sector-heading').show();
                        $('#sector-other').hide();
                        $('#public-sector').show();
                        $('#private-sector').hide();
                        $('#third-sector').hide();
                        break;
                    case "2":
                        $('#sector-heading').show();
                        $('#sector-other').hide();
                        $('#public-sector').hide();
                        $('#private-sector').show();
                        $('#third-sector').hide();
                        break;
                    case "3":
                        $('#sector-heading').show();
                        $('#sector-other').hide();
                        $('#public-sector').hide();
                        $('#private-sector').hide();
                        $('#third-sector').show();
                        break;
                    case "4":
                        $('#sector-heading').hide();
                        $('#sector-other').show();
                        $('#sector-match-label').hide();
                        $('#public-sector').hide();
                        $('#private-sector').hide();
                        $('#third-sector').hide();
                        break;
                }
            } else {
                $('#sector-heading').show();
                $('#sector-match-label').hide();
                $('#public-sector').hide();
                $('#private-sector').hide();
                $('#third-sector').hide();
            }
        });

        $('#GeographicalId').change(function () {
            var $el = $(this).find(':selected');
            var area = $el.attr('value');
            if (area != "default") {
                if (area !== "1") {
                    $('#authority-details').show();
                } else {
                    $('#authority-details').hide();
                }
            }
        });

        $('#ActiveVolunteersId').change(function () {
            var $el = $(this).find(':selected');
            if ($el.val() !== "1") {
                $('#volunteer-info').show();
            } else {
                $('#volunteer-info').hide();
            }
        });

        $('#PaidEmployeesId').change(function () {
            var $el = $(this).find(':selected');
            if ($el.val() !== "11") {
                $('#paid-employee-info').show();
            } else {
                $('#paid-employee-info').hide();
            }
        });

        $('.sector-work-area').change(function () {
            var $el = $(this).find(':selected');
            var workArea = $el.attr('value');
            if (workArea === "Other") {
                $('#sector-work-area-other').show();
            } else {
                $('#sector-work-area-other').hide();
            }
        });
    });
</script>
