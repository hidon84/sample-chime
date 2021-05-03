<script>
import appConfig from '@src/app.config'
import Layout from '@layouts/main.vue'

export default {
  page: {
    title: 'Home',
    meta: [{ name: 'description', content: appConfig.description }],
  },
  components: { Layout },
}
</script>

<template>
  <Layout>
    <div class="sc-jQrCkL cRlvCE"
      ><div class="sc-cZMLWB gbZLHr"
        ><div class="sc-jUotMc gEGKdv"
          ><form
            ><h1 class="sc-dJjZJu fBHXQV" data-testid="heading"
              >Join a meeting</h1
            ><div
              class="sc-bkkfTU gFYNkA ch-form-field-input "
              data-testid="form-field"
              ><label
                data-testid="label"
                class="sc-ieebsP hMyhe ch-input-label"
                for="8925922d-5aeb-4a5a-8054-9a99bb31701f"
                >Meeting Id</label
              ><span
                class="sc-hGPAah bZpGra ch-input-wrapper "
                data-testid="input-wrapper"
                ><input
                  aria-describedby="e8d26d8b-9c17-478d-b562-ce052f3333e9"
                  aria-invalid="false"
                  id="8925922d-5aeb-4a5a-8054-9a99bb31701f"
                  name="meetingId"
                  placeholder="Enter Meeting Id"
                  type="text"
                  class="sc-dlVyqM bwuieu ch-input"
                  data-testid="input"
                  value=""/><button
                  type="button"
                  tabindex="-1"
                  aria-label="clear"
                  class="sc-kfPtPH cMknhK"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="Svg "
                    viewBox="0 0 24 24"
                    width="1.25rem"
                    style="width: 1.25rem;"
                  >
                    <title>Clear</title>
                    <g fill-rule="evenodd" fill="currentColor">
                      <path
                        d="M12 5c3.866 0 7 3.134 7 7s-3.134 7-7 7-7-3.134-7-7 3.134-7 7-7zM9.172 9.17c-.196.196-.196.513 0 .708L11.293 12l-2.12 2.12c-.197.197-.197.513 0 .708.096.098.224.147.352.147.128 0 .256-.05.354-.147L12 12.707l2.121 2.12c.098.099.226.148.353.148.128 0 .256-.05.354-.147.195-.195.195-.511 0-.707L12.708 12l2.12-2.122c.195-.195.195-.512 0-.707-.195-.195-.512-.195-.707 0l-2.12 2.12-2.122-2.12c-.196-.195-.512-.195-.707 0z"
                      ></path>
                    </g></svg></button></span
              ><span
                class="ch-help-text"
                id="e8d26d8b-9c17-478d-b562-ce052f3333e9"
                >Anyone with access to the meeting ID can join</span
              ></div
            ><div
              class="sc-bkkfTU gFYNkA ch-form-field-input "
              data-testid="form-field"
              ><label
                data-testid="label"
                class="sc-ieebsP hMyhe ch-input-label"
                for="9c0116bb-7473-4079-beff-2ce874dff3ed"
                >Name</label
              ><span
                class="sc-hGPAah bZpGra ch-input-wrapper "
                data-testid="input-wrapper"
                ><input
                  aria-invalid="false"
                  id="9c0116bb-7473-4079-beff-2ce874dff3ed"
                  name="name"
                  placeholder="Enter Your Name"
                  type="text"
                  class="sc-dlVyqM bwuieu ch-input"
                  data-testid="input"
                  value=""/><button
                  type="button"
                  tabindex="-1"
                  aria-label="clear"
                  class="sc-kfPtPH cMknhK"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="Svg "
                    viewBox="0 0 24 24"
                    width="1.25rem"
                    style="width: 1.25rem;"
                  >
                    <title>Clear</title>
                    <g fill-rule="evenodd" fill="currentColor">
                      <path
                        d="M12 5c3.866 0 7 3.134 7 7s-3.134 7-7 7-7-3.134-7-7 3.134-7 7-7zM9.172 9.17c-.196.196-.196.513 0 .708L11.293 12l-2.12 2.12c-.197.197-.197.513 0 .708.096.098.224.147.352.147.128 0 .256-.05.354-.147L12 12.707l2.121 2.12c.098.099.226.148.353.148.128 0 .256-.05.354-.147.195-.195.195-.511 0-.707L12.708 12l2.12-2.122c.195-.195.195-.512 0-.707-.195-.195-.512-.195-.707 0l-2.12 2.12-2.122-2.12c-.196-.195-.512-.195-.707 0z"
                      ></path>
                    </g></svg></button></span></div
            ><div
              class="sc-bkkfTU gFYNkA ch-form-field-select "
              data-testid="form-field"
              ><label
                data-testid="label"
                class="sc-ieebsP hMyhe ch-select-label"
                for="9d6fe270-eafc-4c05-bced-03c02b1f5c6a"
                >Meeting region</label
              ><div class="sc-jcFkyM SbOro"
                ><select
                  class="sc-caiKgP bFnFFH ch-select"
                  data-testid="select"
                  id="9d6fe270-eafc-4c05-bced-03c02b1f5c6a"
                  ><option value="">Select a region</option
                  ><option value="us-east-1">United States (N. Virginia)</option
                  ><option value="af-south-1">Africa (Cape Town)</option
                  ><option value="ap-northeast-1">Japan (Tokyo)</option
                  ><option value="ap-northeast-2">Korea (Seoul)</option
                  ><option value="ap-south-1">India (Mumbai)</option
                  ><option value="ap-southeast-1">Singapore</option
                  ><option value="ap-southeast-2">Australia (Sydney)</option
                  ><option value="ca-central-1">Canada</option
                  ><option value="eu-central-1">Germany (Frankfurt)</option
                  ><option value="eu-north-1">Sweden (Stockholm)</option
                  ><option value="eu-south-1">Italy (Milan)</option
                  ><option value="eu-west-1">Ireland</option
                  ><option value="eu-west-2">United Kingdom (London)</option
                  ><option value="eu-west-3">France (Paris)</option
                  ><option value="sa-east-1">Brazil (São Paulo)</option
                  ><option value="us-east-2">United States (Ohio)</option
                  ><option value="us-west-1"
                    >United States (N. California)</option
                  ><option value="us-west-2"
                    >United States (Oregon)</option
                  ></select
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="Svg ch-select-icon"
                  viewBox="0 0 24 24"
                  data-testid="select-icon"
                  style="position: absolute; top: 50%; transform: translateY(-50%); right: 0.2rem; width: 1.5rem; height: 1.5rem;"
                >
                  <g fill-rule="evenodd" fill="currentColor">
                    <path
                      d="M8.824 9.88c-.21.18-.526.154-.705-.056-.159-.187-.156-.457-.006-.64l.063-.065 3.523-3c.165-.14.397-.156.577-.05l.074.052 3.477 3c.209.18.232.497.052.706-.16.185-.428.224-.632.104l-.074-.052-3.151-2.72-3.198 2.722zM15.176 14.12c.21-.18.526-.154.705.056.159.187.157.457.006.64l-.063.065-3.523 3c-.165.14-.397.156-.577.05l-.074-.052-3.477-3c-.209-.18-.232-.497-.052-.706.16-.185.428-.224.632-.104l.074.052 3.151 2.72 3.198-2.722z"
                    ></path>
                  </g></svg></div></div
            ><div
              data-testid="flex"
              class="sc-fFehDp DpDrH"
              style="margin-top: 2.5rem;"
              ><button
                label="Continue"
                class="sc-gsDJrp jAaktH"
                aria-label="Continue"
                data-testid="button"
                ><span class="ch-label" data-testid="button-label"
                  >Continue</span
                ></button
              ></div
            ></form
          ></div
        ><div data-testid="flex" class="sc-fFehDp DpDrH" style="padding: 2rem;"
          ><button
            label="Join via SIP"
            class="sc-gsDJrp juIqtQ"
            aria-label="Join via SIP"
            data-testid="button"
            ><span class="ch-label" data-testid="button-label"
              >Join via SIP</span
            ></button
          ></div
        ></div
      ><span
        style="position: absolute; bottom: 1px; right: 1px; color: rgb(152, 157, 165); font-size: 0.7rem;"
        >amazon-chime-sdk-component-library-react@2.3.0 |
        amazon-chime-sdk-js@2.7.0</span
      ></div
    >
  </Layout>
</template>

<style>
html,
body,
#root {
  height: 100%;
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Lato', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    'Helvetica Neue', Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji',
    'Segoe UI Symbol';
}

*,
*:before,
*:after {
  box-sizing: border-box;
}
</style>

<style data-styled="active" data-styled-version="5.2.3">
.jAaktH {
  border-radius: 0.25rem;
  font-size: 0.875rem;
  padding: 0.5rem 1rem;
  border-color: transparent;
  -webkit-transition: background-color 0.1s ease;
  transition: background-color 0.1s ease;
  display: -webkit-inline-box;
  display: -webkit-inline-flex;
  display: -ms-inline-flexbox;
  display: inline-flex;
  -webkit-align-items: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  background-color: #4fe2f8;
  color: #3f4149;
  border: 0.03125rem solid #000000;
  box-shadow: none;
}
.jAaktH:hover {
  cursor: pointer;
}
.jAaktH:focus {
  outline: none;
}
.jAaktH .ch-icon {
  width: 1.5rem;
  height: 1.5rem;
  margin-right: 0.25rem;
}
.jAaktH:focus {
  background-color: #29dcf8;
  border: 0.03125rem solid #000000;
  color: #3f4149;
  box-shadow: 0 0 0 0.25rem #1fa1b5;
}
.jAaktH:hover {
  background-color: #29dcf8;
  border: 0.03125rem solid #000000;
  color: #3f4149;
  box-shadow: none;
}
.jAaktH:focus:hover {
  box-shadow: 0 0 0 0.25rem #1fa1b5;
}
.jAaktH:active {
  background-color: #22b6cb;
  border: 0.03125rem solid #000000;
  color: #3f4149;
  box-shadow: none;
}
.jAaktH:disabled {
  background-color: #3f4149;
  border: 0.03125rem solid rgba(0, 0, 0, 0.4);
  color: #989da5;
  cursor: not-allowed;
}
.juIqtQ {
  border-radius: 0.25rem;
  font-size: 0.875rem;
  padding: 0.5rem 1rem;
  border-color: transparent;
  -webkit-transition: background-color 0.1s ease;
  transition: background-color 0.1s ease;
  display: -webkit-inline-box;
  display: -webkit-inline-flex;
  display: -ms-inline-flexbox;
  display: inline-flex;
  -webkit-align-items: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  background-color: #7d818b;
  color: #ffffff;
  border: 0.03125rem solid #000000;
  box-shadow: none;
}
.juIqtQ:hover {
  cursor: pointer;
}
.juIqtQ:focus {
  outline: none;
}
.juIqtQ .ch-icon {
  width: 1.5rem;
  height: 1.5rem;
  margin-right: 0.25rem;
}
.juIqtQ:focus {
  background-color: #616672;
  border: 0.03125rem solid #000000;
  color: #ffffff;
  box-shadow: 0 0 0 0.25rem #8aebfa;
}
.juIqtQ:hover {
  background-color: #616672;
  border: 0.03125rem solid #000000;
  color: #ffffff;
  box-shadow: none;
}
.juIqtQ:focus:hover {
  box-shadow: 0 0 0 0.25rem #8aebfa;
}
.juIqtQ:active {
  background-color: #50545e;
  border: 0.03125rem solid #000000;
  color: #ffffff;
  box-shadow: 0 0 0 0.25rem #8aebfa;
}
.juIqtQ:disabled {
  background-color: #3f4149;
  border: 0.03125rem solid rgba(0, 0, 0, 0.6);
  color: #989da5;
  cursor: not-allowed;
}
.DpDrH {
  -webkit-align-items: stretch;
  -webkit-box-align: stretch;
  -ms-flex-align: stretch;
  align-items: stretch;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-basis: auto;
  -ms-flex-preferred-size: auto;
  flex-basis: auto;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
  -webkit-flex-shrink: 1;
  -ms-flex-negative: 1;
  flex-shrink: 1;
  -webkit-flex-wrap: nowrap;
  -ms-flex-wrap: nowrap;
  flex-wrap: nowrap;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  height: 100%;
  -webkit-align-items: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.gFYNkA {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-bottom: 1rem;
  position: relative;
}
.gFYNkA fieldset {
  margin: 0;
  border: none;
  padding: 0;
}
.gFYNkA .ch-help-text {
  font-size: 0.75rem;
  margin-top: 0.5rem;
  color: #ffffff;
}
.gFYNkA legend {
  font-size: 0.875rem;
  color: #ffffff;
  margin-bottom: 0.5rem;
}
.gFYNkA.ch-form-field-input,
.gFYNkA.ch-form-field-select,
.gFYNkA.ch-form-field-textarea {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
}
.gFYNkA.ch-form-field-input label,
.gFYNkA.ch-form-field-select label,
.gFYNkA.ch-form-field-textarea label {
  display: block;
  margin-bottom: 0.5rem;
}
.gFYNkA.ch-form-field-input input,
.gFYNkA.ch-form-field-select input,
.gFYNkA.ch-form-field-textarea input,
.gFYNkA.ch-form-field-input select,
.gFYNkA.ch-form-field-select select,
.gFYNkA.ch-form-field-textarea select {
  width: 100%;
}
.gFYNkA.ch-form-field-checkbox {
  display: grid;
  grid-template-columns: 1.5rem 1fr;
  grid-template-rows: auto;
  gap: 0px 0.5rem;
}
.gFYNkA.ch-form-field-checkbox .ch-checkbox {
  grid-column: 1;
  grid-row: 1;
}
.gFYNkA.ch-form-field-checkbox .ch-checkbox-label {
  line-height: 1.3;
  grid-column: 2;
}
.gFYNkA.ch-form-field-checkbox .ch-help-text {
  grid-row: 2;
  grid-column: 1/3;
}
.gFYNkA.ch-form-field-radiogroup {
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
}
.gFYNkA.ch-form-field-radiogroup .ch-radio-wrapper {
  display: block;
  margin-bottom: 0.5rem;
  padding-left: 0.125rem;
  display: grid;
  grid-template-columns: 1.5rem 1fr;
  grid-template-rows: auto;
  -webkit-align-items: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}
.gFYNkA.ch-form-field-radiogroup .ch-radio-label {
  margin-left: 1rem;
  position: relative;
  bottom: -0.5px;
}
.hMyhe {
  color: #ffffff;
  font-size: 0.875rem;
  line-height: 1.43;
}
.fBHXQV {
  display: block;
  margin: 0;
  font-size: 2.15rem;
  font-weight: normal;
  line-height: 3rem;
}
@media screen and (min-width: 48rem) {
  .fBHXQV {
    font-size: 1.953125rem;
    font-weight: normal;
    line-height: 3.75rem;
  }
}
@media {
  .fBHXQV {
    margin-bottom: 1rem;
  }
}
.bZpGra {
  position: relative;
}
.bZpGra > .ch-icon {
  position: absolute;
  width: 1rem;
  left: 0.1875rem;
  position: absolute;
  top: 54%;
  -webkit-transform: translateY(-50%);
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);
}
.bZpGra > input {
  padding: 0.34375rem 1.75rem 0.34375rem 0.5rem;
}
.bwuieu {
  -webkit-align-items: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-letter-spacing: -0.005625rem;
  -moz-letter-spacing: -0.005625rem;
  -ms-letter-spacing: -0.005625rem;
  letter-spacing: -0.005625rem;
  -webkit-transition: box-shadow 0.05s ease-in;
  transition: box-shadow 0.05s ease-in;
  background-color: #3f4149;
  border: 0.03125rem solid #000000;
  border-radius: 0.25rem;
  box-shadow: 0 0.0625rem 0.0625rem 0 rgba(0, 0, 0, 0.1);
  color: #ffffff;
  font-size: 0.875rem;
  line-height: 1.43;
}
.bwuieu::-webkit-input-placeholder {
  color: #7d818b;
}
.bwuieu::-moz-placeholder {
  color: #7d818b;
}
.bwuieu:-ms-input-placeholder {
  color: #7d818b;
}
.bwuieu::placeholder {
  color: #7d818b;
}
.bwuieu:focus,
.bwuieu[aria-invalid='true']:focus {
  border: solid 0.03125rem #4fe2f8;
  box-shadow: 0 0 0 0.125rem #8aebfa;
  outline: none;
}
.bwuieu[aria-invalid='true'] {
  border: 0.03125rem solid #ff8b8a;
  box-shadow: 0 0 0 0.125rem #fd9b99;
}
.bwuieu::-webkit-search-decoration,
.bwuieu::-webkit-search-cancel-button,
.bwuieu::-webkit-search-results-button,
.bwuieu::-webkit-search-results-decoration {
  display: none;
}
.bwuieu::-ms-clear,
.bwuieu::-ms-reveal {
  display: none;
  width: 0;
  height: 0;
}
.cMknhK {
  position: absolute;
  top: 50%;
  right: 0.125rem;
  -webkit-transform: translateY(-44%);
  -ms-transform: translateY(-44%);
  transform: translateY(-44%);
  border: none;
  background: none;
  cursor: pointer;
  display: none;
}
.cMknhK path {
  fill: #ffffff;
}
.cMknhK:active,
.cMknhK:focus {
  outline: none;
}
.SbOro {
  position: relative;
}
.SbOro .ch-select-icon {
  pointer-events: none;
}
.bFnFFH {
  background-color: #3f4149;
  border: 0.03125rem solid #000000;
  border-radius: 0.25rem;
  box-shadow: 0 0.0625rem 0.0625rem 0 rgba(0, 0, 0, 0.1);
  color: #ffffff;
  font-size: 0.875rem;
  line-height: 1.43;
  height: 2rem;
  -webkit-letter-spacing: -0.005625rem;
  -moz-letter-spacing: -0.005625rem;
  -ms-letter-spacing: -0.005625rem;
  letter-spacing: -0.005625rem;
  width: 100%;
  padding: 0.375rem 1.5rem 0.375rem 0.5rem;
  -webkit-transition: box-shadow 0.05s ease-in;
  transition: box-shadow 0.05s ease-in;
  display: inline-block;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
}
.bFnFFH:focus,
.bFnFFH[aria-invalid='true']:focus {
  border: solid 0.03125rem #4fe2f8;
  box-shadow: 0 0 0 0.125rem #8aebfa;
  outline: none;
}
.bFnFFH[aria-invalid='true'] {
  border: 0.03125rem solid #ff8b8a;
  box-shadow: 0 0 0 0.125rem #fd9b99;
}
html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
  display: block;
}
body {
  line-height: 1;
}
ol,
ul {
  list-style: none;
}
blockquote,
q {
  quotes: none;
}
blockquote:before,
blockquote:after,
q:before,
q:after {
  content: '';
  content: none;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
*,
*::before,
*::after {
  box-sizing: border-box;
}
html {
  font-size: 16px;
  font-family: 'Ember', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  background-color: #3f4149;
  color: #ffffff;
  min-height: 100%;
}
.gbZLHr {
  width: 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
}
@media (min-width: 600px) and (min-height: 600px) {
  .gbZLHr {
    min-height: 35.75rem;
    max-width: 30rem;
    border-radius: 0.25rem;
    box-shadow: 0 0.25rem 0.5rem 0 rgba(0, 0, 0, 0.2),
      0 0.375rem 1.25rem 0 rgba(0, 0, 0, 0.2);
  }
}
.gEGKdv {
  border-bottom: 0.125rem solid #e6e6e6;
  padding: 2rem;
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
}
@media (min-width: 600px) and (min-height: 600px) {
  .gEGKdv {
    padding: 3rem 3rem 2rem;
  }
}
.cRlvCE {
  display: block;
  min-height: 100%;
  margin: auto;
}
@media (min-width: 600px) and (min-height: 600px) {
  .cRlvCE {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-align-items: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    padding: 2rem;
  }
}
</style>
