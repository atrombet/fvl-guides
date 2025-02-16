<template>
  <NuxtLink to="/" class="button-link">
    <button flat class="page__backToHome">
      <i>arrow_back</i>Back to all FVL Guides
    </button>
  </NuxtLink>
  <h1>Tech Booth Startup Sequence</h1>
  <section>
    <h2>Lights</h2>
    <ul>
      <li>
        <h3>Turn on Lighting Mac</h3>
        <p>Vista 3 will automatically open on startup.</p>
      </li>
      <li>
        <h3>Open our show file <code>SundayFay40</code></h3>
      </li>
      <li>
        <h3>Click the Playback page</h3>
        <img src="/img/playback-button.jpg" alt="Vista 3 Playback Page" />
      </li>
      <li>
        <h3 class="flex align-center">
          Select <code class="ml-md">Main</code> <i>arrow_right</i>
          <code>FVL Sermon</code>
        </h3>
        <p>This lighting scene is good enough for most scenarios.</p>
        <img
          src="/img/fvl-sermon-play-button.jpg"
          alt="FVL Sermon lighting scene"
        />
      </li>
    </ul>
  </section>
  <section>
    <h2>ProPresenter & Video</h2>
    <ul>
      <li>
        <h3>Turn on the Sanctuary Switcher</h3>
        <img src="/img/switcher.jpg" alt="Sanctuary Switcher" />
      </li>
      <li>
        <h3>Turn on the External Switcher</h3>
      </li>
      <li>
        <h3>Turn on the Video Rack</h3>
      </li>
      <li>
        <h3>Turn on the Multiview TV</h3>
        <p>
          Set the input to <code>HDMI 1</code> using the remote velco'ed to the
          back to set the TV
        </p>
      </li>
      <li>
        <h3>Turn on ProPresenter Mac</h3>
        <p>ProPresenter will automatically open on startup.</p>
      </li>
      <li>
        <h3>Plug in the Live Camera to turn it on</h3>
      </li>
    </ul>
  </section>
  <section>
    <h2>Sound</h2>
    <ul>
      <li>
        <h3><code>1</code> Turn on battery backup</h3>
        <p>Bottom unit in the Audio Rack</p>
        <p>
          Hold button above left corner of screen until it beeps and let go.
        </p>
      </li>
      <li>
        <h3><code>2</code> Turn on the sound board</h3>
        <p>Switch behind the board on the right hand side.</p>
        <img src="/img/turn-on-board.gif" alt="Sound Board Switch" />
      </li>
      <li>
        <h3>
          <code>3</code> Turn on the power conditioner for the wireless mics
        </h3>
        <p>Top unit in the Audio Rack</p>
        <p>Switch is under a cover that pops up from the bottom.</p>
        <img src="/img/wireless-mic-switch.jpg" alt="Wireless Mics Switch" />
      </li>
      <li>
        <h3><code>4</code> Turn on the LynTec</h3>
        <p>Second unit from the top in the Audio Rack</p>
        <p>Press the green button</p>
        <img src="/img/lyntec-on.jpg" alt="LynTec" />
      </li>
      <li>
        <h3>Set some board levels</h3>
        <p>Main L/R to <code>-5dB</code></p>
        <p>Main C to <code>0dB</code></p>
        <img src="/img/board-levels.gif" alt="Sound Board Levels" />
      </li>
    </ul>
  </section>
</template>

<style scoped>
  img {
    max-width: 300px;
  }
</style>
