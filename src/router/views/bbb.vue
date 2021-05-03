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
    <div class="sc-jIkYaL dFsbRy"
      ><h1 class="sc-dJjZJu kSqBOM" data-testid="heading">Device settings</h1
      ><div class="sc-jOxuqd gXolLs"
        ><div class="sc-hmjpBu LjcBa"
          ><div
            ><h2 class="sc-dJjZJu kyyOEG" data-testid="heading">Audio</h2
            ><div
              class="sc-bkkfTU gFYNkA ch-form-field-select "
              data-testid="form-field"
              ><label
                data-testid="label"
                class="sc-ieebsP hMyhe ch-select-label"
                for="6e6db986-af3e-49f6-8eac-880db6a25dbf"
                >Microphone source</label
              ><div class="sc-jcFkyM SbOro"
                ><select
                  class="sc-caiKgP bFnFFH ch-select"
                  data-testid="select"
                  id="6e6db986-af3e-49f6-8eac-880db6a25dbf"
                  ><option value="default">Default</option
                  ><option
                    value="f11e1ae0c6aee28204d2e9639e15ea048caeb1d87cd114cc8487416997d9f47c"
                    >Built-in Audio Analog Stereo</option
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
            ><div class="sc-ZOsLE jXIWyD"
              ><label
                data-testid="label"
                class="sc-ieebsP hMyhe"
                style="display: block; margin-bottom: 0.5rem;"
                >Microphone activity</label
              ><div class="sc-kHOZQx qriyX"
                ><div
                  class="sc-hOGjNT sDkXQ"
                  style="transform: scaleX(0.859432);"
                ></div></div></div></div
          ><div
            ><div
              class="sc-bkkfTU gFYNkA ch-form-field-select "
              data-testid="form-field"
              ><label
                data-testid="label"
                class="sc-ieebsP hMyhe ch-select-label"
                for="c4a547c8-8a98-4bd5-8b57-a20cd1a4611f"
                >Speaker source</label
              ><div class="sc-jcFkyM SbOro"
                ><select
                  class="sc-caiKgP bFnFFH ch-select"
                  data-testid="select"
                  id="c4a547c8-8a98-4bd5-8b57-a20cd1a4611f"
                  ><option value="default">Default</option
                  ><option
                    value="3785fbb554aa17d9cd13d02d1d0fd105ed2402fb85959b8561e2f93ddee96f21"
                    >Built-in Audio Analog Stereo</option
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
            ><button
              label="Test speakers"
              class="sc-gsDJrp juIqtQ"
              aria-label="Test speakers"
              data-testid="button"
              ><span class="ch-label" data-testid="button-label"
                >Test speakers</span
              ></button
            ></div
          ></div
        ><div class="sc-eLwHGX esa-DDx"
          ><div
            ><h2 class="sc-dJjZJu kyyOEG" data-testid="heading">Video</h2
            ><div class="sc-bTfYlY ZguWT"
              ><div
                class="sc-bkkfTU gFYNkA ch-form-field-select "
                data-testid="form-field"
                ><label
                  data-testid="label"
                  class="sc-ieebsP hMyhe ch-select-label"
                  for="e3efe4e0-f956-4257-9012-108b33a11d7c"
                  >Camera source</label
                ><div class="sc-jcFkyM SbOro"
                  ><select
                    class="sc-caiKgP bFnFFH ch-select"
                    data-testid="select"
                    id="e3efe4e0-f956-4257-9012-108b33a11d7c"
                    ><option
                      value="4570eb503f998d587835af7a974b15fdf7fe5f269124f0ef299fdd7036e0bfc3"
                      >HP TrueVision HD Camera (04f2:b65d)</option
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
                    </g></svg></div></div></div
            ><div class="sc-bTfYlY ZguWT"
              ><div
                class="sc-bkkfTU gFYNkA ch-form-field-select "
                data-testid="form-field"
                ><label
                  data-testid="label"
                  class="sc-ieebsP hMyhe ch-select-label"
                  for="4a276c46-8d34-444e-a6e9-b906ac9aab0a"
                  >Video quality</label
                ><div class="sc-jcFkyM SbOro"
                  ><select
                    class="sc-caiKgP bFnFFH ch-select"
                    data-testid="select"
                    id="4a276c46-8d34-444e-a6e9-b906ac9aab0a"
                    ><option value="unselected">Select video quality</option
                    ><option value="720p"
                      >720p (HD) @ 15 fps (1.4 Mbps max)</option
                    ><option value="540p"
                      >540p (qHD) @ 15 fps (1.4 Mbps max)</option
                    ><option value="360p"
                      >360p (nHD) @ 15 fps (600 Kbps max)</option
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
                    </g></svg></div></div></div
            ><label
              data-testid="label"
              class="sc-ieebsP hMyhe"
              style="display: block; margin-bottom: 0.5rem;"
              >Video preview</label
            ><div
              class="sc-efQUeY cvYBwV sc-GamvQ iBLUvM"
              data-testid="video-tile"
              ><video
                class="ch-video"
                disablepictureinpicture=""
                disableremoteplayback=""
                autoplay="true"
                playsinline="true"
                muted="true"
                style="transform: rotateY(180deg);"
              ></video></div></div></div></div
      ><div data-testid="flex" class="sc-fFehDp dDneiF"
        ><button
          label="Join meeting"
          class="sc-gsDJrp jAaktH"
          aria-label="Join meeting"
          data-testid="button"
          ><span class="ch-label" data-testid="button-label"
            >Join meeting</span
          ></button
        ><label
          data-testid="label"
          class="sc-ieebsP hMyhe"
          style="margin: 0.75rem 0px 0px;"
          >Joining meeting <b>aaaaa</b> as <b>최항돈</b></label
        ></div
      ></div
    >
  </Layout>
</template>

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
.dDneiF {
  -webkit-align-items: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-basis: auto;
  -ms-flex-preferred-size: auto;
  flex-basis: auto;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
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
.kSqBOM {
  display: block;
  margin: 0;
  font-size: 2.90625rem;
  font-weight: normal;
  line-height: 3rem;
}
@media screen and (min-width: 48rem) {
  .kSqBOM {
    font-size: 2.44125rem;
    font-weight: normal;
    line-height: 3.75rem;
  }
}
@media {
  .kSqBOM {
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
  }
}
.kyyOEG {
  display: block;
  margin: 0;
  font-size: 1.18125rem;
  font-weight: normal;
  line-height: 1.5rem;
}
@media screen and (min-width: 48rem) {
  .kyyOEG {
    font-size: 1.25rem;
    font-weight: normal;
    line-height: 1.875rem;
  }
}
@media {
  .kyyOEG {
    text-transform: uppercase;
    font-size: 1rem !important;
    margin-bottom: 1.75rem;
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
.kTvsFx {
  position: absolute;
  top: 50%;
  right: 0.125rem;
  -webkit-transform: translateY(-44%);
  -ms-transform: translateY(-44%);
  transform: translateY(-44%);
  border: none;
  background: none;
  cursor: pointer;
  display: block;
}
.kTvsFx path {
  fill: #ffffff;
}
.kTvsFx:active,
.kTvsFx:focus {
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
.cvYBwV {
  height: 100%;
  width: 100%;
  position: relative;
  background: #1b1c20;
}
.cvYBwV video {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.cvYBwV .ch-icon {
  width: 1.5rem;
  height: 1.5rem;
  display: inline-block;
  background-color: papayawhip;
  margin-right: 0.5rem;
  -webkit-flex: 0 0 1.5rem;
  -ms-flex: 0 0 1.5rem;
  flex: 0 0 1.5rem;
}
.cvYBwV .ch-nameplate {
  -webkit-backdrop-filter: blur(20px);
  backdrop-filter: blur(20px);
  background-color: rgba(46, 47, 52, 0.85);
  border-radius: 0.25rem;
  bottom: 0.5rem;
  color: #ffffff;
  left: 0.5rem;
  max-width: calc(100% - 2rem);
  padding: 0.5rem;
  position: absolute;
}
.cvYBwV .ch-nameplate div {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-align-items: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}
.cvYBwV .ch-nameplate .ch-text {
  font-size: 0.875rem;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
  margin: 0;
}
.iBLUvM {
  height: auto;
  background: unset;
}
.iBLUvM video {
  position: static;
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
.dFsbRy {
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
  min-height: 100%;
  max-width: 85rem;
  padding: 2rem;
  margin: auto;
}
@media (max-width: 760px) {
  .dFsbRy {
    border-right: unset;
    -webkit-align-items: unset;
    -webkit-box-align: unset;
    -ms-flex-align: unset;
    align-items: unset;
    -webkit-box-pack: unset;
    -webkit-justify-content: unset;
    -ms-flex-pack: unset;
    justify-content: unset;
  }
}
.jXIWyD {
  margin-bottom: 2.5rem;
}
.gXolLs {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  width: 100%;
  max-width: 65rem;
  height: auto;
  padding: 1rem 0 3rem 0;
}
.gXolLs > * {
  -webkit-flex-basis: auto;
  -ms-flex-preferred-size: auto;
  flex-basis: auto;
}
@media (min-width: 900px) {
  .gXolLs {
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    padding: 2.5rem 0 6rem 0;
  }
  .gXolLs > * {
    -webkit-flex-basis: 50%;
    -ms-flex-preferred-size: 50%;
    flex-basis: 50%;
  }
  @media (max-height: 800px) {
    .gXolLs {
      padding: 2rem 0 2rem;
    }
  }
}
.LjcBa {
  padding: 0 3rem 0 0;
  border-right: 0.125rem solid #e6e6e6;
}
@media (max-width: 900px) {
  .LjcBa {
    padding: 2rem 0 2rem 0;
    border-right: unset;
  }
}
.esa-DDx {
  padding: 0 0 0 3rem;
}
@media (max-width: 900px) {
  .esa-DDx {
    padding: 0;
  }
}
.ZguWT {
  margin-bottom: 1.5rem;
}
.qriyX {
  width: 100%;
  height: 0.625rem;
  background-color: #ecf0f1;
  border-radius: 0.25rem;
}
.sDkXQ {
  height: 0.625rem;
  background-color: #18bc9c;
  border-radius: 0.25rem;
  -webkit-transform: scaleX(0);
  -ms-transform: scaleX(0);
  transform: scaleX(0);
  -webkit-transform-origin: left;
  -ms-transform-origin: left;
  transform-origin: left;
  -webkit-transition: -webkit-transform 33ms ease-in-out;
  -webkit-transition: transform 33ms ease-in-out;
  transition: transform 33ms ease-in-out;
  will-change: transform;
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
.dDneiF {
  -webkit-align-items: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-basis: auto;
  -ms-flex-preferred-size: auto;
  flex-basis: auto;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
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
.kSqBOM {
  display: block;
  margin: 0;
  font-size: 2.90625rem;
  font-weight: normal;
  line-height: 3rem;
}
@media screen and (min-width: 48rem) {
  .kSqBOM {
    font-size: 2.44125rem;
    font-weight: normal;
    line-height: 3.75rem;
  }
}
@media {
  .kSqBOM {
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
  }
}
.kyyOEG {
  display: block;
  margin: 0;
  font-size: 1.18125rem;
  font-weight: normal;
  line-height: 1.5rem;
}
@media screen and (min-width: 48rem) {
  .kyyOEG {
    font-size: 1.25rem;
    font-weight: normal;
    line-height: 1.875rem;
  }
}
@media {
  .kyyOEG {
    text-transform: uppercase;
    font-size: 1rem !important;
    margin-bottom: 1.75rem;
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
.kTvsFx {
  position: absolute;
  top: 50%;
  right: 0.125rem;
  -webkit-transform: translateY(-44%);
  -ms-transform: translateY(-44%);
  transform: translateY(-44%);
  border: none;
  background: none;
  cursor: pointer;
  display: block;
}
.kTvsFx path {
  fill: #ffffff;
}
.kTvsFx:active,
.kTvsFx:focus {
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
.cvYBwV {
  height: 100%;
  width: 100%;
  position: relative;
  background: #1b1c20;
}
.cvYBwV video {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.cvYBwV .ch-icon {
  width: 1.5rem;
  height: 1.5rem;
  display: inline-block;
  background-color: papayawhip;
  margin-right: 0.5rem;
  -webkit-flex: 0 0 1.5rem;
  -ms-flex: 0 0 1.5rem;
  flex: 0 0 1.5rem;
}
.cvYBwV .ch-nameplate {
  -webkit-backdrop-filter: blur(20px);
  backdrop-filter: blur(20px);
  background-color: rgba(46, 47, 52, 0.85);
  border-radius: 0.25rem;
  bottom: 0.5rem;
  color: #ffffff;
  left: 0.5rem;
  max-width: calc(100% - 2rem);
  padding: 0.5rem;
  position: absolute;
}
.cvYBwV .ch-nameplate div {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-align-items: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}
.cvYBwV .ch-nameplate .ch-text {
  font-size: 0.875rem;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
  margin: 0;
}
.iBLUvM {
  height: auto;
  background: unset;
}
.iBLUvM video {
  position: static;
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
.dFsbRy {
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
  min-height: 100%;
  max-width: 85rem;
  padding: 2rem;
  margin: auto;
}
@media (max-width: 760px) {
  .dFsbRy {
    border-right: unset;
    -webkit-align-items: unset;
    -webkit-box-align: unset;
    -ms-flex-align: unset;
    align-items: unset;
    -webkit-box-pack: unset;
    -webkit-justify-content: unset;
    -ms-flex-pack: unset;
    justify-content: unset;
  }
}
.jXIWyD {
  margin-bottom: 2.5rem;
}
.gXolLs {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  width: 100%;
  max-width: 65rem;
  height: auto;
  padding: 1rem 0 3rem 0;
}
.gXolLs > * {
  -webkit-flex-basis: auto;
  -ms-flex-preferred-size: auto;
  flex-basis: auto;
}
@media (min-width: 900px) {
  .gXolLs {
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    padding: 2.5rem 0 6rem 0;
  }
  .gXolLs > * {
    -webkit-flex-basis: 50%;
    -ms-flex-preferred-size: 50%;
    flex-basis: 50%;
  }
  @media (max-height: 800px) {
    .gXolLs {
      padding: 2rem 0 2rem;
    }
  }
}
.LjcBa {
  padding: 0 3rem 0 0;
  border-right: 0.125rem solid #e6e6e6;
}
@media (max-width: 900px) {
  .LjcBa {
    padding: 2rem 0 2rem 0;
    border-right: unset;
  }
}
.esa-DDx {
  padding: 0 0 0 3rem;
}
@media (max-width: 900px) {
  .esa-DDx {
    padding: 0;
  }
}
.ZguWT {
  margin-bottom: 1.5rem;
}
.qriyX {
  width: 100%;
  height: 0.625rem;
  background-color: #ecf0f1;
  border-radius: 0.25rem;
}
.sDkXQ {
  height: 0.625rem;
  background-color: #18bc9c;
  border-radius: 0.25rem;
  -webkit-transform: scaleX(0);
  -ms-transform: scaleX(0);
  transform: scaleX(0);
  -webkit-transform-origin: left;
  -ms-transform-origin: left;
  transform-origin: left;
  -webkit-transition: -webkit-transform 33ms ease-in-out;
  -webkit-transition: transform 33ms ease-in-out;
  transition: transform 33ms ease-in-out;
  will-change: transform;
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
