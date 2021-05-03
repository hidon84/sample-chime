<script>
import appConfig from '@src/app.config'

export default {
  page: {
    title: 'Home',
    meta: [{ name: 'description', content: appConfig.description }],
  },
  components: {},
}
</script>

<template>
  <main class="sc-fvxABq ksYiKe"
    ><div class="sc-fbyett efQrIY"
      ><div class="sc-iAKVOt dFzFlg videos" data-testid="video-grid"
        ><div class="sc-efQUeY jvGrMY sc-faUofl GxhMR" data-testid="video-tile"
          ><video
            class="ch-video"
            disablepictureinpicture=""
            disableremoteplayback=""
            autoplay="true"
            playsinline="true"
            muted="true"
            style="transform: rotateY(180deg); object-fit: cover;"
            src="https://cdn.cloudflare.steamstatic.com/steam/apps/256832952/movie480_vp9.webm?t=1619885244"
          ></video
          ><header class="ch-nameplate"><p class="ch-text">Me</p></header></div
        ><div data-testid="flex" class="sc-fFehDp DpDrH"
          ><div data-testid="flex" class="sc-fFehDp fWJHoC"
            ><h1 class="sc-dJjZJu bJGRYM" data-testid="heading"
              >Meeting information</h1
            ><dl class="sc-GEcJY bWacXU"
              ><div><dt>Meeting ID</dt><dd>aaaaa</dd></div
              ><div><dt>Hosted region</dt><dd>ap-northeast-2</dd></div></dl
            ><button
              label="Light mode"
              class="sc-gsDJrp dfrJkv"
              aria-label="Light mode"
              data-testid="button"
              ><span class="ch-label" data-testid="button-label"
                >Light mode</span
              ></button
            ></div
          ></div
        ></div
      ><div class="sc-bXTfsO fnTMrZ controls"
        ><div class="sc-jrQzUz ejhOMq controls-menu" data-testid="control-bar"
          ><div
            data-testid="control-bar-item"
            class="sc-kDThTU dFxXZy mobile-toggle"
            ><span class="sc-dkPtyc ibSPGT"
              ><button
                label="Menu"
                class="sc-gsDJrp epjxQv ch-control-bar-item-iconButton"
                aria-label="Menu"
                data-testid="button"
                ><span class="ch-icon" data-testid="button-icon"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="Svg "
                    viewBox="0 0 24 24"
                  >
                    <g fill-rule="evenodd" fill="currentColor">
                      <path
                        d="M12 4c4.418 0 8 3.582 8 8s-3.582 8-8 8-8-3.582-8-8 3.582-8 8-8zm0 1c-3.86 0-7 3.14-7 7 0 3.859 3.14 7 7 7 3.859 0 7-3.141 7-7 0-3.86-3.141-7-7-7zm-3 6c.552 0 1 .448 1 1s-.448 1-1 1-1-.448-1-1 .448-1 1-1zm6 0c.553 0 1 .448 1 1s-.447 1-1 1c-.553 0-1-.448-1-1s.447-1 1-1zm-3 0c.552 0 1 .448 1 1s-.448 1-1 1-1-.448-1-1 .448-1 1-1z"
                      ></path>
                    </g></svg></span
                ><span class="ch-label" data-testid="button-label"
                  >Menu</span
                ></button
              ></span
            ><div class="ch-control-bar-item-label">Menu</div></div
          ><div data-testid="control-bar-item" class="sc-kDThTU dFxXZy"
            ><span class="sc-dkPtyc ibSPGT"
              ><button
                label="Mute"
                class="sc-gsDJrp epjxQv ch-control-bar-item-iconButton"
                aria-label="Mute"
                data-testid="button"
                ><span class="ch-icon" data-testid="button-icon"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="Svg sc-pVTma WSLlv"
                    viewBox="0 0 24 24"
                    data-testid="good-connection-mic"
                  >
                    <title>Microphone</title>
                    <g fill-rule="evenodd" fill="currentColor">
                      <path
                        d="M14.5 19c.276 0 .5.224.5.5s-.224.5-.5.5h-5c-.276 0-.5-.224-.5-.5s.224-.5.5-.5zm3-7.5c.276 0 .5.224.5.5 0 3.309-2.691 6-6 6s-6-2.691-6-6c0-.276.224-.5.5-.5s.5.224.5.5c0 2.757 2.243 5 5 5s5-2.243 5-5c0-.276.224-.5.5-.5zM12 4c1.654 0 3 1.448 3 3.227v4.546C15 13.552 13.654 15 12 15s-3-1.448-3-3.227V7.227C9 5.447 10.346 4 12 4zm0 1c-1.103 0-2 .999-2 2.227v4.546C10 13 10.897 14 12 14s2-1 2-2.227V7.227C14 5.999 13.103 5 12 5z"
                      ></path>
                    </g></svg></span
                ><span class="ch-label" data-testid="button-label"
                  >Mute</span
                ></button
              ></span
            ><span data-testid="popover"
              ><span
                ><span class="sc-dkPtyc ibSPGT"
                  ><button
                    class="sc-gsDJrp epjxQv ch-control-bar-item-caret "
                    aria-label="Mute"
                    aria-haspopup="true"
                    aria-expanded="false"
                    data-testid="button"
                    label="Mute"
                    ><span class="ch-icon" data-testid="button-icon"
                      ><svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="Svg sc-gKckTs fXFdhJ"
                        viewBox="0 0 24 24"
                        direction="up"
                        data-testid="control-bar-item-caret"
                      >
                        <g fill-rule="evenodd" fill="currentColor">
                          <path
                            transform-origin="center"
                            d="M8.824 13.88c-.21.18-.526.154-.705-.056-.159-.187-.156-.457-.006-.64l.063-.065 3.523-3c.165-.14.397-.156.577-.05l.074.052 3.477 3c.209.18.232.497.052.706-.16.185-.428.224-.632.104l-.074-.052-3.151-2.72-3.198 2.722z"
                          ></path>
                        </g></svg></span
                    ><span class="ch-label" data-testid="button-label"
                      >Mute</span
                    ></button
                  ></span
                ></span
              ></span
            ><div class="ch-control-bar-item-label">Mute</div></div
          ><div data-testid="control-bar-item" class="sc-kDThTU dFxXZy"
            ><span class="sc-dkPtyc ibSPGT"
              ><button
                label="Video"
                class="sc-gsDJrp epjxQv ch-control-bar-item-iconButton"
                aria-label="Video"
                data-testid="button"
                ><span class="ch-icon" data-testid="button-icon"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="Svg "
                    viewBox="0 0 24 24"
                  >
                    <g fill-rule="evenodd" fill="currentColor">
                      <path
                        d="M19 14.164c0 .176-.131.262-.187.29-.052.027-.234.1-.416-.028l-2.256-1.622v-.001c-.09-.064-.141-.16-.141-.262v-1.082c0-.102.051-.197.141-.262l2.255-1.622c.081-.057.159-.075.227-.075.09 0 .16.03.19.046.056.029.187.115.187.29v4.328zm-4 .336c0 .828-.673 1.5-1.5 1.5h-7c-.827 0-1.5-.672-1.5-1.5v-5C5 8.673 5.673 8 6.5 8h7c.827 0 1.5.673 1.5 1.5v5zm4.27-5.843c-.471-.242-1.028-.202-1.457.106L16 10.066V9.5C16 8.122 14.879 7 13.5 7h-7C5.121 7 4 8.122 4 9.5v5C4 15.879 5.121 17 6.5 17h7c1.379 0 2.5-1.121 2.5-2.5v-.566l1.814 1.304c.243.174.527.262.813.262.219 0 .438-.051.643-.156.45-.231.73-.683.73-1.18V9.837c0-.497-.28-.95-.73-1.18z"
                      ></path>
                    </g></svg></span
                ><span class="ch-label" data-testid="button-label"
                  >Video</span
                ></button
              ></span
            ><span data-testid="popover"
              ><span
                ><span class="sc-dkPtyc ibSPGT"
                  ><button
                    class="sc-gsDJrp epjxQv ch-control-bar-item-caret "
                    aria-label="Video"
                    aria-haspopup="true"
                    aria-expanded="false"
                    data-testid="button"
                    label="Video"
                    ><span class="ch-icon" data-testid="button-icon"
                      ><svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="Svg sc-gKckTs fXFdhJ"
                        viewBox="0 0 24 24"
                        direction="up"
                        data-testid="control-bar-item-caret"
                      >
                        <g fill-rule="evenodd" fill="currentColor">
                          <path
                            transform-origin="center"
                            d="M8.824 13.88c-.21.18-.526.154-.705-.056-.159-.187-.156-.457-.006-.64l.063-.065 3.523-3c.165-.14.397-.156.577-.05l.074.052 3.477 3c.209.18.232.497.052.706-.16.185-.428.224-.632.104l-.074-.052-3.151-2.72-3.198 2.722z"
                          ></path>
                        </g></svg></span
                    ><span class="ch-label" data-testid="button-label"
                      >Video</span
                    ></button
                  ></span
                ></span
              ></span
            ><div class="ch-control-bar-item-label">Video</div></div
          ><div data-testid="control-bar-item" class="sc-kDThTU dFxXZy"
            ><span class="sc-dkPtyc ibSPGT"
              ><button
                label="Content"
                class="sc-gsDJrp epjxQv ch-control-bar-item-iconButton"
                aria-label="Content"
                data-testid="button"
                ><span class="ch-icon" data-testid="button-icon"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="Svg "
                    viewBox="0 0 24 24"
                  >
                    <title>Screen share</title>
                    <g fill-rule="evenodd" fill="currentColor">
                      <path
                        d="M15.5 17c.276 0 .5.224.5.5s-.224.5-.5.5h-7c-.276 0-.5-.224-.5-.5s.224-.5.5-.5zM18 6c1.103 0 2 .897 2 2v6c0 1.103-.897 2-2 2H6c-1.103 0-2-.897-2-2V8c0-1.103.897-2 2-2zm0 1H6c-.552 0-1 .449-1 1v6c0 .551.448 1 1 1h12c.552 0 1-.449 1-1V8c0-.551-.448-1-1-1z"
                      ></path>
                    </g></svg></span
                ><span class="ch-label" data-testid="button-label"
                  >Content</span
                ></button
              ></span
            ><div class="ch-control-bar-item-label">Content</div></div
          ><div data-testid="control-bar-item" class="sc-kDThTU dFxXZy"
            ><span class="sc-dkPtyc ibSPGT"
              ><button
                label="Speaker"
                class="sc-gsDJrp epjxQv ch-control-bar-item-iconButton"
                aria-label="Speaker"
                data-testid="button"
                ><span class="ch-icon" data-testid="button-icon"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="Svg "
                    viewBox="0 0 24 24"
                  >
                    <g fill-rule="evenodd" fill="currentColor">
                      <path
                        d="M10.939 7.26c.397-.295.914-.343 1.361-.123.431.213.7.638.7 1.11v7.506c0 .473-.269.898-.7 1.111-.187.092-.386.137-.582.137-.28 0-.557-.091-.788-.269l-2.486-1.727c-.088-.061-.194-.094-.302-.094H6.256c-.693 0-1.256-.552-1.256-1.229v-3.357c0-.681.566-1.236 1.263-1.236h1.88c.108 0 .214-.033.3-.092zm5.148.054c.176-.211.49-.241.704-.065 1.406 1.164 2.213 2.896 2.213 4.751 0 1.855-.807 3.588-2.213 4.752-.094.077-.207.115-.319.115-.144 0-.286-.061-.385-.18-.177-.213-.147-.529.065-.705 1.177-.974 1.852-2.425 1.852-3.982 0-1.556-.675-3.007-1.852-3.981-.212-.176-.242-.492-.065-.705zm-4.23.719c-.041-.02-.183-.077-.32.029l-.018.013-2.505 1.742c-.255.178-.556.272-.871.272h-1.88c-.145 0-.263.106-.263.236v3.357c0 .127.115.229.256.229h1.886c.315 0 .617.095.874.274l2.503 1.741c.157.117.298.062.337.042.054-.027.144-.09.144-.215V8.247c0-.125-.09-.187-.143-.214zm2.841 1.62c.181-.21.496-.232.705-.053.707.608 1.112 1.483 1.112 2.4 0 .917-.405 1.793-1.112 2.402-.095.08-.21.12-.326.12-.14 0-.28-.058-.379-.173-.18-.21-.156-.524.053-.705.486-.42.764-1.018.764-1.644 0-.625-.278-1.223-.764-1.642-.209-.181-.233-.496-.053-.705z"
                      ></path>
                    </g></svg></span
                ><span class="ch-label" data-testid="button-label"
                  >Speaker</span
                ></button
              ></span
            ><span data-testid="popover"
              ><span
                ><span class="sc-dkPtyc ibSPGT"
                  ><button
                    class="sc-gsDJrp epjxQv ch-control-bar-item-caret "
                    aria-label="Speaker"
                    aria-haspopup="true"
                    aria-expanded="false"
                    data-testid="button"
                    label="Speaker"
                    ><span class="ch-icon" data-testid="button-icon"
                      ><svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="Svg sc-gKckTs fXFdhJ"
                        viewBox="0 0 24 24"
                        direction="up"
                        data-testid="control-bar-item-caret"
                      >
                        <g fill-rule="evenodd" fill="currentColor">
                          <path
                            transform-origin="center"
                            d="M8.824 13.88c-.21.18-.526.154-.705-.056-.159-.187-.156-.457-.006-.64l.063-.065 3.523-3c.165-.14.397-.156.577-.05l.074.052 3.477 3c.209.18.232.497.052.706-.16.185-.428.224-.632.104l-.074-.052-3.151-2.72-3.198 2.722z"
                          ></path>
                        </g></svg></span
                    ><span class="ch-label" data-testid="button-label"
                      >Speaker</span
                    ></button
                  ></span
                ></span
              ></span
            ><div class="ch-control-bar-item-label">Speaker</div></div
          ><div data-testid="control-bar-item" class="sc-kDThTU dFxXZy"
            ><span class="sc-dkPtyc ibSPGT"
              ><button
                label="Leave"
                class="sc-gsDJrp epjxQv ch-control-bar-item-iconButton"
                aria-label="Leave"
                data-testid="button"
                ><span class="ch-icon" data-testid="button-icon"
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="Svg "
                    viewBox="0 0 24 24"
                  >
                    <g fill-rule="evenodd" fill="currentColor">
                      <path
                        d="M11.999 10.19c.738 0 3.194.089 3.792 1.241.08.158.117.315.138.418l.228 1.112c.033.167.116.318.239.438l.423.414c.349.341.919.343 1.27 0l.649-.635c.308-.3.347-.777.09-1.107-.776-1.005-2.696-2.698-6.83-2.771-4.132.073-6.052 1.766-6.828 2.77-.257.331-.218.808.09 1.108l.649.635c.349.341.919.343 1.27 0L7.6 13.4c.124-.121.207-.272.24-.438l.228-1.116c.02-.1.058-.257.137-.412.599-1.155 3.055-1.244 3.793-1.244m5.455 4.877c-.483 0-.966-.18-1.334-.539l-.422-.413c-.266-.26-.447-.59-.521-.953l-.23-1.115c-.008-.047-.022-.113-.046-.158-.145-.28-1.17-.699-2.902-.699-1.732 0-2.757.419-2.903.702-.023.042-.037.108-.046.152l-.23 1.119c-.073.362-.254.692-.521.953l-.421.412c-.736.719-1.932.719-2.668 0l-.65-.635c-.67-.656-.75-1.703-.181-2.435.887-1.146 3.056-3.08 7.61-3.158h.019c4.555.078 6.724 2.012 7.61 3.159.569.731.49 1.778-.181 2.434l-.65.635c-.367.359-.85.539-1.333.539"
                      ></path>
                    </g></svg></span
                ><span class="ch-label" data-testid="button-label"
                  >Leave</span
                ></button
              ></span
            ><div class="ch-control-bar-item-label">Leave</div></div
          ></div
        ></div
      ></div
    ><div
      data-testid="navigation-bar"
      class="sc-fFehDp jEiCKR sc-giYgFv fDRFhs nav"
      ><div title="Navigation" class="sc-llYToB oNoBb"
        ><span class="ch-title">Navigation</span
        ><span class="sc-dkPtyc ibSPGT"
          ><button
            class="sc-gsDJrp epjxQv ch-btn-close"
            label="Close"
            aria-label="Close"
            data-testid="button"
            ><span class="ch-icon" data-testid="button-icon"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                class="Svg "
                viewBox="0 0 24 24"
              >
                <g fill-rule="evenodd" fill="currentColor">
                  <path
                    d="M14.5 5C16.981 5 19 7.019 19 9.5v5c0 2.481-2.019 4.5-4.5 4.5h-5C7.019 19 5 16.981 5 14.5v-5C5 7.019 7.019 5 9.5 5zm0 1h-5C7.57 6 6 7.57 6 9.5v5C6 16.43 7.57 18 9.5 18h5c1.93 0 3.5-1.57 3.5-3.5v-5C18 7.57 16.43 6 14.5 6zM9.172 9.17c.195-.194.511-.194.707 0L12 11.293l2.121-2.121c.195-.195.512-.195.707 0 .195.195.195.512 0 .707L12.708 12l2.12 2.12c.195.197.195.513 0 .708-.098.098-.226.147-.354.147-.127 0-.255-.05-.353-.147l-2.12-2.121-2.122 2.12c-.098.099-.226.148-.354.148-.128 0-.256-.05-.353-.147-.196-.195-.196-.511 0-.707L11.293 12l-2.12-2.122c-.197-.195-.197-.512 0-.707z"
                  ></path>
                </g></svg></span
            ><span class="ch-label" data-testid="button-label"
              >Close</span
            ></button
          ></span
        ></div
      ><div data-testid="navbar-item" class="sc-iJKOzS hgAJDS"
        ><span class="sc-dkPtyc ibSPGT"
          ><button
            label="Attendees"
            class="sc-gsDJrp epjxQv"
            aria-label="Attendees"
            data-testid="button"
            ><span class="ch-icon" data-testid="button-icon"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                class="Svg "
                viewBox="0 0 24 24"
              >
                <g fill-rule="evenodd" fill="currentColor">
                  <path
                    d="M12.105 12.923c1.596 0 2.895 1.3 2.895 2.895v2.105H6v-2.105c0-1.596 1.299-2.895 2.895-2.895zm3.767.571c.139-.24.447-.32.684-.182.89.517 1.444 1.477 1.444 2.506v1.605c0 .277-.223.5-.5.5-.276 0-.5-.223-.5-.5v-1.605c0-.673-.362-1.302-.946-1.641-.238-.138-.32-.444-.182-.683zm-3.767.43h-3.21c-1.045 0-1.895.85-1.895 1.894v1.105h7v-1.105c0-1.045-.85-1.895-1.895-1.895zM10.645 6c1.654 0 3 1.346 3 3s-1.346 3-3 3-3-1.346-3-3 1.346-3 3-3zm3.385.488c.096-.259.386-.39.642-.298 1.18.433 1.972 1.562 1.972 2.81s-.793 2.377-1.972 2.81c-.057.02-.115.03-.172.03-.204 0-.396-.126-.47-.328-.095-.26.038-.547.298-.642.787-.288 1.316-1.04 1.316-1.87 0-.83-.529-1.582-1.316-1.87-.26-.095-.393-.383-.298-.642zM10.645 7c-1.104 0-2 .897-2 2s.896 2 2 2c1.103 0 2-.897 2-2s-.897-2-2-2z"
                  ></path>
                </g></svg></span
            ><span class="ch-label" data-testid="button-label"
              >Attendees</span
            ></button
          ></span
        ><label class="ch-navigation-bar-item-label" data-testid="navbar-label"
          >Attendees</label
        ></div
      ><div data-testid="navbar-item" class="sc-iJKOzS hgAJDS"
        ><span class="sc-dkPtyc ibSPGT"
          ><button
            label="Light mode"
            class="sc-gsDJrp epjxQv"
            aria-label="Light mode"
            data-testid="button"
            ><span class="ch-icon" data-testid="button-icon"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                class="Svg "
                viewBox="0 0 24 24"
              >
                <g fill-rule="evenodd" fill="currentColor">
                  <path
                    d="M12.006 7c2.627 0 4.897 1.813 6.339 3.334.888.934.888 2.398 0 3.332-1.442 1.52-3.712 3.334-6.34 3.334-2.626 0-4.897-1.813-6.34-3.335-.887-.933-.887-2.396.002-3.331C7.107 8.814 9.379 7 12.006 7zm0 1c-2.392 0-4.544 1.893-5.614 3.023-.512.539-.512 1.415-.001 1.954 1.07 1.13 3.223 3.022 5.615 3.022 2.39 0 4.544-1.893 5.613-3.022.513-.539.513-1.415 0-1.954C16.55 9.893 14.398 8 12.007 8zm0 1c1.653 0 3 1.346 3 3s-1.347 3-3 3c-1.655 0-3-1.346-3-3s1.345-3 3-3zm0 1c-1.104 0-2 .897-2 2s.896 2 2 2c1.102 0 2-.897 2-2s-.898-2-2-2z"
                  ></path>
                </g></svg></span
            ><span class="ch-label" data-testid="button-label"
              >Light mode</span
            ></button
          ></span
        ><label class="ch-navigation-bar-item-label" data-testid="navbar-label"
          >Light mode</label
        ></div
      ><div data-testid="navbar-item" class="sc-iJKOzS hgAJDS"
        ><span class="sc-dkPtyc ibSPGT"
          ><button
            label="Meeting metrics"
            class="sc-gsDJrp epjxQv"
            aria-label="Meeting metrics"
            data-testid="button"
            ><span class="ch-icon" data-testid="button-icon"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                class="Svg "
                viewBox="0 0 24 24"
              >
                <g fill-rule="evenodd" fill="currentColor">
                  <path
                    d="M12 4c4.411 0 8 3.589 8 8s-3.589 8-8 8-8-3.589-8-8 3.589-8 8-8zm0 1c-3.859 0-7 3.141-7 7s3.141 7 7 7 7-3.141 7-7-3.141-7-7-7zm.016 6.476c.276 0 .5.224.5.5v2.498c0 .276-.224.5-.5.5s-.5-.224-.5-.5v-2.498c0-.276.224-.5.5-.5zM12 8.709c.414 0 .75.335.75.75 0 .414-.336.75-.75.75s-.75-.336-.75-.75c0-.415.336-.75.75-.75z"
                  ></path>
                </g></svg></span
            ><span class="ch-label" data-testid="button-label"
              >Meeting metrics</span
            ></button
          ></span
        ><label class="ch-navigation-bar-item-label" data-testid="navbar-label"
          >Meeting metrics</label
        ></div
      ></div
    ></main
  >
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
.dfrJkv {
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
  margin-top: 32px;
}
.dfrJkv:hover {
  cursor: pointer;
}
.dfrJkv:focus {
  outline: none;
}
.dfrJkv .ch-icon {
  width: 1.5rem;
  height: 1.5rem;
  margin-right: 0.25rem;
}
.dfrJkv:focus {
  background-color: #29dcf8;
  border: 0.03125rem solid #000000;
  color: #3f4149;
  box-shadow: 0 0 0 0.25rem #1fa1b5;
}
.dfrJkv:hover {
  background-color: #29dcf8;
  border: 0.03125rem solid #000000;
  color: #3f4149;
  box-shadow: none;
}
.dfrJkv:focus:hover {
  box-shadow: 0 0 0 0.25rem #1fa1b5;
}
.dfrJkv:active {
  background-color: #22b6cb;
  border: 0.03125rem solid #000000;
  color: #3f4149;
  box-shadow: none;
}
.dfrJkv:disabled {
  background-color: #3f4149;
  border: 0.03125rem solid rgba(0, 0, 0, 0.4);
  color: #989da5;
  cursor: not-allowed;
}
.epjxQv {
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
  background-color: transparent;
  color: #e4e9f2;
  border: 0 solid #000000;
  border-radius: 50%;
  padding: 0.1875rem;
  position: relative;
}
.epjxQv:hover {
  cursor: pointer;
}
.epjxQv:focus {
  outline: none;
}
.epjxQv .ch-icon {
  width: 1.5rem;
  height: 1.5rem;
  margin-right: 0.25rem;
}
.epjxQv > .ch-label {
  -webkit-clip: rect(1px, 1px, 1px, 1px);
  clip: rect(1px, 1px, 1px, 1px);
  height: 1px;
  width: 1px;
  overflow: hidden;
  position: absolute !important;
}
.epjxQv > .ch-icon {
  width: 1.5rem;
  height: 1.5rem;
  margin: 0;
}
.epjxQv:focus {
  background-color: transparent;
  border: 0.03125rem solid #000000;
  color: #3f4149;
  color: #e4e9f2;
  box-shadow: 0 0 0 0.25rem #22b6cb;
}
.epjxQv:hover {
  background-color: #29dcf8;
  border: 0.03125rem solid #000000;
  color: #3f4149;
}
.epjxQv:active {
  background-color: #22b6cb;
  border: 0.03125rem solid #000000;
  color: #3f4149;
}
.epjxQv:disabled {
  background-color: transparent;
  border: none;
  color: #989da5;
  cursor: not-allowed;
}
.epjxQv + * {
  position: absolute;
  font-size: 0.55rem;
  z-index: 1;
  top: -15%;
  left: 76%;
}
.ibSPGT {
  display: inline-block;
  position: relative;
}
.fXFdhJ {
  -webkit-transform: rotate(0deg);
  -ms-transform: rotate(0deg);
  transform: rotate(0deg);
}
.ejhOMq {
  display: -webkit-inline-box;
  display: -webkit-inline-flex;
  display: -ms-inline-flexbox;
  display: inline-flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-align-items: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  border-radius: 0.25rem;
  background-color: #1b1c20;
  opacity: 1;
  border: none;
  box-shadow: 0 0.75rem 1.875rem 0 rgba(0, 0, 0, 0.15);
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
  height: 5rem;
}
@media screen and (max-width: 35.5rem) {
  .ejhOMq {
    top: unset;
    bottom: unset;
    right: unset;
    left: unset;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    width: 100%;
    bottom: 0;
    position: fixed;
    box-shadow: 0 0.75rem 1.875rem 0 rgba(0, 0, 0, 0.15);
    border: none;
    width: 100%;
  }
}
@media screen and (max-width: 20rem) {
  .ejhOMq {
    -webkit-box-pack: space-around;
    -webkit-justify-content: space-around;
    -ms-flex-pack: space-around;
    justify-content: space-around;
    top: unset;
    bottom: unset;
    right: unset;
    left: unset;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    width: 100%;
    bottom: 0;
    position: fixed;
    box-shadow: 0 0.75rem 1.875rem 0 rgba(0, 0, 0, 0.15);
    border: none;
  }
}
.dFxXZy {
  margin: 0 0.625rem;
  display: grid;
  grid-template-rows: 1.5rem 1rem;
  justify-items: center;
  -webkit-align-items: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  grid-template-columns: 2.5rem minmax(0.5rem, auto);
}
.dFxXZy > :first-child {
  grid-column-start: 1;
}
.dFxXZy .ch-control-bar-item-iconButton .ch-icon {
  width: 1.5rem;
  height: 1.5rem;
  border-radius: 100%;
}
.dFxXZy .ch-control-bar-item-caret {
  width: 1.25rem;
  height: 1.25rem;
  padding: 0;
}
.dFxXZy .ch-control-bar-item-caret .ch-icon {
  width: 100%;
  height: 100%;
}
.dFxXZy .ch-control-bar-item-caret .Svg g {
  -webkit-transform: scale(1.333);
  -ms-transform: scale(1.333);
  transform: scale(1.333);
  -webkit-transform-origin: 50% 50%;
  -ms-transform-origin: 50% 50%;
  transform-origin: 50% 50%;
}
.dFxXZy .ch-control-bar-popover {
  background-color: inherit;
  grid-column-start: 1;
  color: #e4e9f2;
}
.dFxXZy .ch-control-bar-popover .isOpen.ch-control-bar-item-caret {
  color: #4fe2f8;
}
.dFxXZy .ch-control-bar-item-label {
  color: #e4e9f2;
  grid-row-start: 2;
  font-size: 0.65rem;
  padding-top: 0.25rem;
  justify-self: center;
  grid-column: 1;
}
@media screen and (max-width: 35.5rem) {
  .dFxXZy {
    -webkit-box-pack: space-around;
    -webkit-justify-content: space-around;
    -ms-flex-pack: space-around;
    justify-content: space-around;
  }
  .dFxXZy button ~ span {
    display: none;
  }
}
@media screen and (max-width: 20rem) {
  .dFxXZy {
    margin: 0;
  }
  .dFxXZy button ~ span {
    display: none;
  }
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
.fWJHoC {
  -webkit-align-items: stretch;
  -webkit-box-align: stretch;
  -ms-flex-align: stretch;
  align-items: stretch;
  display: block;
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
  margin-bottom: 2rem;
  padding-left: 1rem;
  padding-right: 1rem;
}
@media screen and (min-width: 48rem) {
  .fWJHoC {
    margin-right: 2rem;
  }
}
.jEiCKR {
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
.bJGRYM {
  display: block;
  margin: 0;
  font-size: 2.15rem;
  font-weight: normal;
  line-height: 3rem;
  margin-bottom: 8px;
}
@media screen and (min-width: 48rem) {
  .bJGRYM {
    font-size: 1.953125rem;
    font-weight: normal;
    line-height: 3.75rem;
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
.oNoBb {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 3rem;
  -webkit-align-items: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  border-bottom: 0.03125rem solid #000000;
  padding: 1rem;
}
.oNoBb .ch-title {
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
}
.oNoBb .ch-btn-close {
  margin-left: auto;
  margin-right: 1rem;
}
@media screen and (min-width: 48rem) {
  .oNoBb {
    display: none;
  }
}
.hgAJDS {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-align-items: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  width: 4.25rem;
  min-height: 3rem;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  padding: 0 0.25rem;
}
.hgAJDS .ch-navigation-bar-item-label {
  text-align: center;
  display: none;
  font-size: 0.65rem;
  width: 100%;
  padding: 0 0.25rem;
  margin-bottom: 1.5rem;
}
.fDRFhs {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  height: 100%;
  max-width: 100%;
  color: #ffffff;
  background-color: #1b1c20;
  width: 4.25rem;
  padding-top: 1rem;
}
@media screen and (max-width: 48rem) {
  .fDRFhs {
    width: 20rem;
    padding-top: 0;
  }
  .fDRFhs .sc-llYToB {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }
  .fDRFhs .sc-iJKOzS {
    width: auto;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
  }
  .fDRFhs .sc-iJKOzS .ch-navigation-bar-item-label {
    font-size: 1rem;
    text-align: left;
    margin-left: 1.5rem;
    margin-bottom: 0;
    display: block;
  }
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
.dFzFlg {
  position: relative;
  display: grid;
  height: 100%;
  width: 100%;
  overflow: auto;
  background-color: #2e2f34;
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
.jvGrMY {
  height: 100%;
  width: 100%;
  position: relative;
  background: #1b1c20;
}
.jvGrMY video {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.jvGrMY .ch-icon {
  width: 1.5rem;
  height: 1.5rem;
  display: inline-block;
  background-color: papayawhip;
  margin-right: 0.5rem;
  -webkit-flex: 0 0 1.5rem;
  -ms-flex: 0 0 1.5rem;
  flex: 0 0 1.5rem;
}
.jvGrMY .ch-nameplate {
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
.jvGrMY .ch-nameplate div {
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
.jvGrMY .ch-nameplate .ch-text {
  font-size: 0.875rem;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
  margin: 0;
}
@media {
  .jvGrMY {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    position: absolute;
    bottom: 1rem;
    right: 1rem;
    width: 20vw;
    max-height: 30vh;
    height: auto;
  }
  .jvGrMY video {
    position: static;
  }
}
.fnUKAX {
  display: none;
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
.ksYiKe {
  height: 100vh;
  width: 100%;
  display: grid;
  grid-template-columns: auto 1fr;
  grid-template-areas: 'nav content';
}
.ksYiKe .video-content {
  grid-area: content;
}
.ksYiKe .nav {
  grid-area: nav;
}
.ksYiKe .roster {
  grid-area: roster;
  z-index: 2;
}
@media screen and (min-width: 769px) {
  .ksYiKe .mobile-toggle {
    display: none;
  }
}
@media screen and (max-width: 768px) {
  .ksYiKe {
    grid-template-columns: 1fr;
    grid-template-areas: 'content';
  }
  .ksYiKe .nav {
    grid-area: unset;
    position: fixed;
  }
  .ksYiKe .roster {
    grid-area: unset;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    max-width: 320px;
  }
}
@media screen and (max-width: 460px) {
  .ksYiKe .roster {
    max-width: 100%;
  }
}
.jHnfGs {
  height: 100vh;
  width: 100%;
  display: grid;
  grid-template-columns: 1fr;
  grid-template-areas: 'content';
}
.jHnfGs .video-content {
  grid-area: content;
}
.jHnfGs .nav {
  grid-area: nav;
}
.jHnfGs .roster {
  grid-area: roster;
  z-index: 2;
}
@media screen and (min-width: 769px) {
  .jHnfGs .mobile-toggle {
    display: none;
  }
}
@media screen and (max-width: 768px) {
  .jHnfGs {
    grid-template-columns: 1fr;
    grid-template-areas: 'content';
  }
  .jHnfGs .nav {
    grid-area: unset;
    position: fixed;
  }
  .jHnfGs .roster {
    grid-area: unset;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    max-width: 320px;
  }
}
@media screen and (max-width: 460px) {
  .jHnfGs .roster {
    max-width: 100%;
  }
}
.efQrIY {
  position: relative;
  grid-area: content;
  height: 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
}
.efQrIY .videos {
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
}
.efQrIY .controls {
  position: absolute;
  bottom: 1rem;
  left: 50%;
  -webkit-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  transform: translateX(-50%);
}
@media screen and (max-width: 768px) {
  .efQrIY .controls {
    position: static;
    -webkit-transform: unset;
    -ms-transform: unset;
    transform: unset;
  }
}
.bWacXU {
  font-size: 1rem;
}
.bWacXU dt {
  display: inline-block;
  margin-bottom: 0.75rem;
  margin-right: 0.5rem;
}
.bWacXU dt::after {
  content: ':';
}
.bWacXU dd {
  display: inline-block;
  font-weight: 600;
}
.fnTMrZ {
  opacity: 0;
  -webkit-transition: opacity 250ms ease;
  transition: opacity 250ms ease;
}
@media screen and (max-width: 768px) {
  .fnTMrZ {
    opacity: 1;
  }
}
.fnTMrZ .controls-menu {
  width: 100%;
  position: static;
}
.jnjgRQ {
  opacity: 1;
  -webkit-transition: opacity 250ms ease;
  transition: opacity 250ms ease;
}
@media screen and (max-width: 768px) {
  .jnjgRQ {
    opacity: 1;
  }
}
.jnjgRQ .controls-menu {
  width: 100%;
  position: static;
}
</style>
