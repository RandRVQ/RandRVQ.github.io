---
title: "Audio Examples"
layout: single
permalink: /audio
author_profile: false
# classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
excerpt: "Experimental results" # "Here you can find the audio files of the different pieces we worked on." - Example of a subtitle
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
---
<html>

</html>


Welcome to the audio examples page. 

---
# Audio compression reconstruction results

## Reconstructions

These results are presented in the table 1a of the paper, and audio examples are shown below.

> Reconstructions
<html>
  <table>
    <thread>
      <tr>
        <th>
          <!-- <center> Voice </center> -->
        </th>
        <th>
          <center> Original </center>
        </th>
        <th>
          <center> Baseline </center>
        </th>
        <th>
          <center> RandRVQ1 </center>
        </th>
        <th>
          <center> RandRVQ4 </center>
        </th>
        <th>
          <center> RandRVQ5 </center>
        </th>
      </tr>
    </thread>
    <tbody>
      <tr>
        <th> <strong> Sample 1 </strong> </th>
        <th>
          <audio class="px-1" controls="" controlslist="nodownload">
            <source src="audio/source_samples/sample_0.wav" type="audio/wav">
          </audio>
        </th>
        <th>
          <audio controls="">
            <source src="audio/baseline_output_samples/sample_0.wav"/>
          </audio>
        </th>
        <th>
          <audio controls="">
            <source src="audio/8192_1024_output_samples/sample_0.wav"/>
          </audio>
        </th>
        <th>
          <audio controls="">
            <source src="audio/16384_512_output_samples/sample_0.wav"/>
          </audio>
        </th>
        <th>
          <audio controls="">
            <source src="audio/16384_512_6rq_output_samples/sample_0.wav"/>
          </audio>
        </th>
      </tr>
    </tbody>
  </table>
</html>
<br/>

