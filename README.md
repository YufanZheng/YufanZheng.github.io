# 

## About Me


## Education

## Publications

## Research Experience

## Awards

## Talks

## Skills



<body>
  <table style="width:100%;max-width:800px;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
    <tr style="padding:0px">
      <td style="padding:0px">
        <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
          <tr style="padding:0px">
            <td style="padding:2.5%;width:63%;vertical-align:middle">
              <p style="text-align:center">
                <name>Jon Barron</name>
              </p>
              <p>I am a staff research scientist at <a href="https://ai.google/research">Google Research</a>, where I work on computer vision and machine learning.
              </p>
              <p>
                At Google I've worked on <a href="https://ai.googleblog.com/2020/12/portrait-light-enhancing-portrait.html">Portrait Light</a>, <a href="https://ai.googleblog.com/2014/04/lens-blur-in-new-google-camera-app.html">Lens Blur</a>, <a href="https://ai.googleblog.com/2014/10/hdr-low-light-and-high-dynamic-range.html">HDR+</a>, <a href="https://www.google.com/get/cardboard/jump/">Jump</a>, <a href="https://ai.googleblog.com/2017/10/portrait-mode-on-pixel-2-and-pixel-2-xl.html">Portrait Mode</a>, and <a href="https://www.youtube.com/watch?v=JSnB06um5r4">Glass</a>. I did my PhD at <a href="http://www.eecs.berkeley.edu/">UC Berkeley</a>, where I was advised by <a href="http://www.cs.berkeley.edu/~malik/">Jitendra Malik</a> and funded by the <a href="http://www.nsfgrfp.org/">NSF GRFP</a>. I did my bachelors at the <a href="http://cs.toronto.edu">University of Toronto</a>.
                I've received the <a href="https://www2.eecs.berkeley.edu/Students/Awards/15/">C.V. Ramamoorthy Distinguished Research Award</a> and the <a href="https://www.thecvf.com/?page_id=413#YRA">PAMI Young Researcher Award</a>.
              </p>
              <p style="text-align:center">
                <a href="mailto:jonbarron@gmail.com">Email</a> &nbsp/&nbsp
                <a href="data/JonBarron-CV.pdf">CV</a> &nbsp/&nbsp
                <a href="data/JonBarron-bio.txt">Bio</a> &nbsp/&nbsp
                <a href="https://scholar.google.com/citations?hl=en&user=jktWnL8AAAAJ">Google Scholar</a> &nbsp/&nbsp
                <a href="https://twitter.com/jon_barron">Twitter</a> &nbsp/&nbsp
                <a href="https://github.com/jonbarron/">Github</a>
              </p>
            </td>
            <td style="padding:2.5%;width:40%;max-width:40%">
              <a href="images/JonBarron.jpg"><img style="width:100%;max-width:100%" alt="profile photo" src="images/JonBarron_circle.jpg" class="hoverZoomLink"></a>
            </td>
          </tr>
        </tbody></table>
        <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
            <tr>
            <td style="padding:20px;width:100%;vertical-align:middle">
              <heading>Research</heading>
              <p>
                I'm interested in computer vision, machine learning, optimization, and image processing. Much of my research is about inferring the physical world (shape, motion, color, light, etc) from images. Representative papers are <span class="highlight">highlighted</span>.
              </p>
            </td>
          </tr>
		
		
        </tbody></table>
        <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>

          <tr onmouseout="hypernerf_stop()" onmouseover="hypernerf_start()">
            <td style="padding:20px;width:25%;vertical-align:middle">
              <div class="one">
                <div class="two" id='hypernerf_image'><video  width=100% height=100% muted autoplay loop>
                <source src="images/hypernerf_after.mp4" type="video/mp4">
                Your browser does not support the video tag.
                </video></div>
                <img src='images/hypernerf_before.jpg' width="160">
              </div>
              <script type="text/javascript">
                function hypernerf_start() {
                  document.getElementById('hypernerf_image').style.opacity = "1";
                }

                function hypernerf_stop() {
                  document.getElementById('hypernerf_image').style.opacity = "0";
                }
                hypernerf_stop()
              </script>
            </td>
            <td style="padding:20px;width:75%;vertical-align:middle">
              <a href="https://hypernerf.github.io/">
                <papertitle>HyperNeRF: A Higher-Dimensional Representation
for Topologically Varying Neural Radiance Fields</papertitle>
              </a>
              <br>
							<a href="https://keunhong.com">Keunhong Park</a>,
							<a href="https://utkarshsinha.com">Utkarsh Sinha</a>, 
							<a href="https://phogzone.com/">Peter Hedman</a>,
              <strong>Jonathan T. Barron</strong>, <br>
							<a href="http://sofienbouaziz.com">Sofien Bouaziz</a>,
							<a href="https://www.danbgoldman.com">Dan B Goldman</a>,
							<a href="http://www.ricardomartinbrualla.com">Ricardo Martin-Brualla</a>, 
							<a href="https://homes.cs.washington.edu/~seitz/">Steven M. Seitz</a>
              <br>
              <em>SIGGRAPH Asia</em>, 2021 
              <br>
              <a href="https://hypernerf.github.io/">project page</a>
              /
              <a href="https://arxiv.org/abs/2106.13228">arXiv</a>
              <p></p>
              <p>Applying ideas from level set methods to NeRF lets you represent scenes that deform and change shape.</p>
            </td>
          </tr> 

          <tr onmouseout="nerfactor_stop()" onmouseover="nerfactor_start()">
            <td style="padding:20px;width:25%;vertical-align:middle">
              <div class="one">
                <div class="two" id='nerfactor_image'>
                  <img src='images/nerfactor_after.png' width="160"></div>
                <img src='images/nerfactor_before.png' width="160">
              </div>
              <script type="text/javascript">
                function nerfactor_start() {
                  document.getElementById('nerfactor_image').style.opacity = "1";
                }

                function nerfactor_stop() {
                  document.getElementById('nerfactor_image').style.opacity = "0";
                }
                nerfactor_stop()
              </script>
            </td>
            <td style="padding:20px;width:75%;vertical-align:middle">
              <a href="https://people.csail.mit.edu/xiuming/projects/nerfactor/">
              <papertitle>NeRFactor: Neural Factorization of Shape and Reflectance<br>
Under an Unknown Illumination</papertitle>
              </a>
              <br>
              <a href="https://people.csail.mit.edu/xiuming/">Xiuming Zhang</a>,
              <a href="https://pratulsrinivasan.github.io/">Pratul Srinivasan</a>,
              <a href="https://boyangdeng.com/">Boyang Deng</a>,<br>
              <a href="https://www.pauldebevec.com/">Paul Debevec</a>,
              <a href="http://billf.mit.edu/">William T. Freeman</a>,
							<strong>Jonathan T. Barron</strong>
              <br>
              <em>SIGGRAPH Asia</em>, 2021 
              <br>
              <a href="https://people.csail.mit.edu/xiuming/projects/nerfactor/">project page</a>
              /
              <a href="https://arxiv.org/abs/2106.01970">arXiv</a>
              /
              <a href="https://www.youtube.com/watch?v=UUVSPJlwhPg">video</a>
              <p></p>
              <p>By placing priors on illumination and materials, we can recover NeRF-like models of the intrinsics of a scene from a single multi-image capture.</p>
            </td>

          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle">
              <img src="images/B3DO.jpg" alt="b3do" width="160" style="border-style: none">
            </td>
            <td width="75%" valign="middle">
              <a href="https://drive.google.com/file/d/1_S8EQyngbHQrB415o0XkQ4V9SMzdEgWT/view?usp=sharing">
                <papertitle>A Category-Level 3-D Object Dataset: Putting the Kinect to Work</papertitle>
              </a>
              <br>
              <a href="http://www.eecs.berkeley.edu/%7Eallie/">Allison Janoch</a>,
              <a href="http://sergeykarayev.com/">Sergey Karayev</a>,
              <a href="http://www.eecs.berkeley.edu/%7Ejiayq/">Yangqing Jia</a>,
              <strong>Jonathan T. Barron</strong>,
              <a href="http://www.cs.berkeley.edu/%7Emfritz/">Mario Fritz</a>,
              <a href="http://www.icsi.berkeley.edu/%7Esaenko/">Kate Saenko</a>,
              <a href="http://www.eecs.berkeley.edu/%7Etrevor/">Trevor Darrell</a>
              <br>
              <em>ICCV 3DRR Workshop</em>, 2011
              <br>
              <a href="data/B3DO_ICCV_2011.bib">bibtex</a> /
              <a href="https://drive.google.com/file/d/1qf4-U5RhSw12O7gzQwW66SMQhs2FWYDW/view?usp=sharing">"smoothing" code</a>
              <p>We present a large RGB-D dataset of indoor scenes and investigate ways to improve object detection using depth information.</p>
            </td>
          </tr>

          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle">
              <img src="images/safs.jpg" alt="safs_small" width="160" height="160" style="border-style: none">
            </td>
            <td width="75%" valign="middle">
              <a href="https://drive.google.com/file/d/1EZTOO5xezLYcyIFgAzs4KuZFLbTcwTDH/view?usp=sharing">
                <papertitle>High-Frequency Shape and Albedo from Shading using Natural Image Statistics</papertitle>
              </a>
              <br>
              <strong>Jonathan T. Barron</strong>, <a href="http://www.cs.berkeley.edu/~malik/">Jitendra Malik</a>
              <br>
              <em>CVPR</em>, 2011
              <br>
              <a href="data/BarronMalikCVPR2011.bib">bibtex</a>
              <p>This paper is subsumed by <a href="#SIRFS">SIRFS</a>.</p>
            </td>
          </tr>

          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle">
              <img src="images/fast_texture.jpg" alt="fast-texture" width="160" height="160">
            </td>
            <td width="75%" valign="middle">
              <a href="https://drive.google.com/file/d/1rc05NatkQVmUDlGCAYcHSrvAzTpU9knT/view?usp=sharing">
                <papertitle>Discovering Efficiency in Coarse-To-Fine Texture Classification</papertitle>
              </a>
              <br>
              <strong>Jonathan T. Barron</strong>, <a href="http://www.cs.berkeley.edu/~malik/">Jitendra Malik</a>
              <br>
              <em>Technical Report</em>, 2010
              <br>
              <a href="data/BarronTR2010.bib">bibtex</a>
              <p>A model and feature representation that allows for sub-linear coarse-to-fine semantic segmentation.
              </p>
            </td>
          </tr>

          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle">
              <img src="images/prl.jpg" alt="prl" width="160" height="160">
            </td>
            <td width="75%" valign="middle">
              <a href="https://drive.google.com/file/d/13rVuJpcytRdLYCnKpq46g7B7IzSrPQ2P/view?usp=sharing">
                <papertitle>Parallelizing Reinforcement Learning</papertitle>
              </a>
              <br>
              <strong>Jonathan T. Barron</strong>, <a href="http://www.eecs.berkeley.edu/~dsg/">Dave Golland</a>, <a href="http://www.cs.berkeley.edu/~nickjhay/">Nicholas J. Hay</a>
              <br>
              <em>Technical Report</em>, 2009
              <br>
              <a href="data/BarronPRL2009.bib">bibtex</a>
              <p>Markov Decision Problems which lie in a low-dimensional latent space can be decomposed, allowing modified RL algorithms to run orders of magnitude faster in parallel.</p>
            </td>
          </tr>

          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle">
              <img src="images/bd_promo.jpg" alt="blind-date" width="160" height="160">
            </td>
            <td width="75%" valign="middle">
              <a href="https://drive.google.com/file/d/1PQjzKgFcrAesMIDJr-WDlCwuGUxZJZwO/view?usp=sharing">
                <papertitle>Blind Date: Using Proper Motions to Determine the Ages of Historical Images</papertitle>
              </a>
              <br>
              <strong>Jonathan T. Barron</strong>, <a href="http://cosmo.nyu.edu/hogg/">David W. Hogg</a>, <a href="http://www.astro.princeton.edu/~dstn/">Dustin Lang</a>, <a href="http://cs.nyu.edu/~roweis/">Sam Roweis</a>
              <br>
              <em>The Astronomical Journal</em>, 136, 2008
              <p>Using the relative motions of stars we can accurately estimate the date of origin of historical astronomical images.</p>
            </td>
          </tr>

          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle">
              <img src="images/clean_promo.jpg" alt="clean-usnob" width="160" height="160">
            </td>
            <td width="75%" valign="middle">
              <a href="https://drive.google.com/file/d/1YvRx-4hrZoCk-nl6OgVJZlHAqOiN5hWq/view?usp=sharing">
                <papertitle>Cleaning the USNO-B Catalog Through Automatic Detection of Optical Artifacts</papertitle>
              </a>
              <br>
              <strong>Jonathan T. Barron</strong>, <a href="http://stumm.ca/">Christopher Stumm</a>, <a href="http://cosmo.nyu.edu/hogg/">David W. Hogg</a>, <a href="http://www.astro.princeton.edu/~dstn/">Dustin Lang</a>, <a href="http://cs.nyu.edu/~roweis/">Sam Roweis</a>
              <br>
              <em>The Astronomical Journal</em>, 135, 2008
              <p>We use computer vision techniques to identify and remove diffraction spikes and reflection halos in the USNO-B Catalog.</p>
              <p>In use at <a href="http://www.astrometry.net">Astrometry.net</a></p>
            </td>
          </tr>

        </tbody></table>

        <table width="100%" align="center" border="0" cellspacing="0" cellpadding="20"><tbody>
          <tr>
            <td>
              <heading>Service</heading>
            </td>
          </tr>
        </tbody></table>
        <table width="100%" align="center" border="0" cellpadding="20"><tbody>
          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle"><img src="images/cvf.jpg"></td>
            <td width="75%" valign="center">
              <a href="http://cvpr2021.thecvf.com/area-chairs">Area Chair, Longuet-Higgins Award Committee Member, CVPR 2021</a>
              <br><br>
              <a href="http://cvpr2019.thecvf.com/area_chairs">Area Chair, CVPR 2019</a>
              <br><br>
              <a href="http://cvpr2018.thecvf.com/organizers/area_chairs">Area Chair, CVPR 2018</a>
            </td>
          </tr>
          <tr>
            <td style="padding:20px;width:25%;vertical-align:middle">
              <img src="images/cs188.jpg" alt="cs188">
            </td>
            <td width="75%" valign="center">
              <a href="http://inst.eecs.berkeley.edu/~cs188/sp11/announcements.html">Graduate Student Instructor, CS188 Spring 2011</a>
              <br>
              <br>
              <a href="http://inst.eecs.berkeley.edu/~cs188/fa10/announcements.html">Graduate Student Instructor, CS188 Fall 2010</a>
              <br>
              <br>
              <a href="http://aima.cs.berkeley.edu/">Figures, "Artificial Intelligence: A Modern Approach", 3rd Edition</a>
            </td>
          </tr>
        </tbody></table>
	      
        
      </td>
    </tr>
  </table>
</body>

