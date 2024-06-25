---
clicks: 6
---
# The Data-driven Research Platform for Neurotechnology - Dareplane


<div id='dareplane_setup_div' v-after>
  <img id="dareplane_setup" src="/images/dareplane_setup_for_dark_bg.svg">
  <a href="https://github.com/bsdlab/Dareplane/">https://github.com/bsdlab/Dareplane/</a>
</div>



<!-- This makes an object appear on one click and disappear on another -->
<!-- TODO: Make this highlighting better once I have a better understanding of how vue works -->


<!-- Copydraw -->
<div v-click-hide="2">
  <div v-click="1">
    <img id="copyDraw_Test" src="/images/copyDraw_Test.svg#svgView(viewBox(150, 80, 400, 200))">
    <div id="copydraw_focus" class='focusbox'></div> 
  </div>
</div>

<div v-click-hide="3">
  <div v-click="2">
    <div class='eeg_10chan_bg_wrapper_full'>
      <div class='eeg_10chan'>
      </div> 
    </div>

  <div id="input_focus" class='focusbox'></div>
  </div>
</div>


<!-- Decoding -->
<div v-click-hide="4">
  <div v-click="3">

  <div class='eeg_10chan_bg_wrapper'>
    <div class='eeg_10chan'>
    </div> 
  </div>

  <img id="eeg_decoding" src="/images/overview_dbs_modulate_component_all_horizontalLayout.svg#svgView(viewBox(260, -2, 70, 120))">

  <div class='control_in_background_wrapper_bottom'>
    <div id='single_control_bg_right'>
    </div> 
  </div>

  <div id="decoding_focus" class='focusbox'></div>

  </div>
</div>

<!-- Control -->
<div v-click-hide="5">
  <div v-click="4">

  <div class='control_in_background_wrapper_dp'>
    <div id='single_control_bg_dp'>
    </div> 
  </div>

  <img id="control_logic" src="/images/pid_control_logic_dark_bg.svg">

  <div class='control_out_background_wrapper'>
    <div id='control_bg'>
    </div> 
  </div>

  <div id="control_focus" class='focusbox'></div>

  </div>
</div>

<!-- stimulation pulses -->
<div v-click-hide="6">
  <div v-click="5">

  <img id="closed_loop_example_traces" src="/images/closed_loop_example_traces.svg">

  <div id="ipg_focus" class='focusbox'></div>

  </div>
</div>


<!-- Control Room -->
<div v-click-hide="7">
  <div v-click="6">

  <img id="control_room_svg" src="/images/web_gui.svg">
  <div id="control_room_focus" class='focusbox'></div>

  </div>
</div>

<style>
.eeg_10chan_bg_wrapper {
  top: 20%;
}
</style>
