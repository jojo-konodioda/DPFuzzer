Details about path planners we investigated are available in `investigated_planners` directory.

# RQ1
Code for replaying these scenarios is available in `RQ1` directory.

## Videos

### 8 types of vulnerabilities

<p align = "center">
<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">#1</b>
  </div>
  <img src="RQ1/gifs/type1/type1-1.gif" alt="image" style="width: auto; height: 360px;">
</div>

<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">#2</b>
  </div>
  <img src="RQ1/gifs/type2/type2-1.gif" alt="image" style="width: auto; height: 360px;">
</div>
</p>

<p align = "center">
<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">#3</b>
  </div>
  <img src="RQ1/gifs/type3/type3-1.gif" alt="image" style="width: auto; height: 360px;">
</div>

<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">#4</b>
  </div>
  <img src="RQ1/gifs/type4/type4.gif" alt="image" style="width: auto; height: 360px;">
</div>
</p>

<p align = "center">
<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">#5</b>
  </div>
  <img src="RQ1/gifs/type5/type5.gif" alt="image" style="width: auto; height: 360px;">
</div>

<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">#6</b>
  </div>
  <img src="RQ1/gifs/type6/type6-1.gif" alt="image" style="width: auto; height: 360px;">
</div>
</p>

<p align = "center">
<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">#7</b>
  </div>
  <img src="RQ1/gifs/type7/type7-1.gif" alt="image" style="width: auto; height: 360px;">
</div>

<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">#8</b>
  </div>
  <img src="RQ1/gifs/type8/type8-1.gif" alt="image" style="width: auto; height: 360px;">
</div>
</p>

# RQ2
Data in RQ2 is available in `RQ2` directory.

# RQ3
## Comparison
The comparison show the drone can reach destination in empty scenario or scenario with randomly arranged obstacles.

<p align = "center">
<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">Empty</b>
  </div>
  <img src="RQ3/comparison/empty.gif" alt="image" style="width: auto; height: 240px;">
</div>

<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">Random1</b>
  </div>
  <img src="RQ3/comparison/random1.gif" alt="image" style="width: auto; height: 240px;">
</div>

<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">Random2</b>
  </div>
  <img src="RQ3/comparison/random2.gif" alt="image" style="width: auto; height: 240px;">
</div>
</p>

## Case1
<p align = "center">
<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">Simulator</b>
  </div>
  <img src="RQ3/case1/simulator.gif" alt="image" style="width: auto; height: 360px;">
</div>
</p>

<p align = "center">
<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">Real world 1</b>
  </div>
  <img src="RQ3/case1/realworld1.gif" alt="image" style="width: auto; height: 360px;">
</div>

<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">Real world 2</b>
  </div>
  <img src="RQ3/case1/realworld2.gif" alt="image" style="width: auto; height: 360px;">
</div>
</p>


# Fixing
## Case1
Adjusted parameters
```bash
optimization/lambda_smooth:     1.0 -> 0.4
optimization/lambda_collision:  1.0 -> 3.0
```
<p align = "center">
<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">Before</b>
  </div>
  <img src="fixing/type1/before.gif" alt="image" style="width: auto; height: 360px;">
</div>

<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">After</b>
  </div>
  <img src="fixing/type1/after.gif" alt="image" style="width: auto; height: 360px;">
</div>
</p>

## Case2
Adjusted parameters
```bash
manager/feasibility_tolerance:  0.05 -> 0.15
optimization/lambda_smooth:     1.0 -> 0.6
```
<p align = "center">
<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">Before</b>
  </div>
  <img src="fixing/type3/before.gif" alt="image" style="width: auto; height: 360px;">
</div>

<div style="position: relative; display: inline-block;">
  <div style="position: absolute; top: 0; left: 0; background-color: rgba(255, 255, 255, 0.9); padding: 8px;">
    <b style="font-size: 32px;">After</b>
  </div>
  <img src="fixing/type3/after.gif" alt="image" style="width: auto; height: 360px;">
</div>
</p>
