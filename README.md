# Algorithms for Self-Driving Car

This project is done for self-learning experience of different popular autonomous
driving algorithms. 

Most algorithms are based on [Udacity Self-Driving Car Engineer Nanodegree](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013).

## Progress

- [x] Basic lane finding
- [x] Advanced lane finding
- [x] Kalman filters
- [x] Particle filter
- [ ] Path planning
- [ ] Model predictive control
- [ ] RRT, RRT*

## Results

<table style="width:100%">
  <tr>
    <th><p>
           <a href="https://www.youtube.com/watch?v=mbqWboRy95Q">
           <img src="https://github.com/huuanhhuynguyen/basic_lane_finding/blob/master/data/corner.gif"
            alt="basic lane finding" width="130" height="100"></a>
           <br>Basic Lane Finding
           <br><a href="https://github.com/huuanhhuynguyen/basic_lane_finding">(code)</a>
      </p>
    </th>
    <th><p>
           <a href="https://www.youtube.com/watch?v=4fW9n5syoqE">
           <img src="https://github.com/huuanhhuynguyen/advanced_lane_finding/blob/master/data/thumbnail.gif"
            alt="Advanced lane finding" width="130" height="100"></a>
           <br>Advanced Lane Finding
           <br><a href="https://github.com/huuanhhuynguyen/advanced_lane_finding">(code)</a>
        </p>
    </th>
    <th><p>
           <a href="https://github.com/huuanhhuynguyen/kalman_filters/blob/master/out/ekf_fusion_3.png">
           <img src="https://github.com/huuanhhuynguyen/kalman_filters/blob/master/out/ekf_fusion_3.png"
            alt="Kalman filters" width="130" height="100"></a>
           <br>Ext./ Unsc. Kalman Filters
           <br><a href="https://github.com/huuanhhuynguyen/kalman_filters">(code)</a>
        </p>
    </th>
    <th><p>
           <a href="https://www.youtube.com/watch?v=qKuo6CHQeHk">
           <img src="https://github.com/huuanhhuynguyen/particle_filters/blob/master/demo.gif"
            alt="Particle filter" width="130" height="100"></a>
           <br>Particle Filter
           <br><a href="https://github.com/huuanhhuynguyen/particle_filters">(code)</a>
        </p>
    </th>
  </tr>
</table>

## Clone and Build

Clone the project and checkout master branch on each submodule.
```
$ git clone https://github.com/huuanhhuynguyen/self-driving-car.git --recursive
$ git submodule foreach "git checkout master"
```
Every submodule has its own build instruction described in its README.
