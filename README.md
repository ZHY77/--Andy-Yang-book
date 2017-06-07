# 前言

Introduction

2017.4.26

  
p.p1 {margin: 0.0px 0.0px 0.0px 0.0px; font: 18.0px Menlo; color: \#000000}  
p.p2 {margin: 0.0px 0.0px 0.0px 0.0px; font: 18.0px Menlo; color: \#3e1e81}  
p.p3 {margin: 0.0px 0.0px 0.0px 0.0px; font: 18.0px Menlo; color: \#3c828b}  
p.p4 {margin: 0.0px 0.0px 0.0px 0.0px; font: 18.0px Menlo; color: \#703daa}  
p.p5 {margin: 0.0px 0.0px 0.0px 0.0px; font: 18.0px Menlo; color: \#c42275}  
span.s1 {font-variant-ligatures: no-common-ligatures}  
span.s2 {font-variant-ligatures: no-common-ligatures; color: \#c42275}  
span.s3 {font-variant-ligatures: no-common-ligatures; color: \#6122ae}  
span.s4 {font-variant-ligatures: no-common-ligatures; color: \#000000}  
span.s5 {font-variant-ligatures: no-common-ligatures; color: \#539aa4}  
span.s6 {font-variant-ligatures: no-common-ligatures; color: \#703daa}  
span.s7 {font-variant-ligatures: no-common-ligatures; color: \#3e1e81}  


- \(BOOL\)application:\(UIApplication\*\)application didFinishLaunchingWithOptions:\(NSDictionary\*\)launchOptions {

self.window= \[\[UIWindowalloc\]initWithFrame:\[UIScreenmainScreen\].bounds\];

ViewController\* V = \[\[ViewControlleralloc\]init\];

 V.view.backgroundColor= \[UIColorredColor\];

self.window.rootViewController= V;

 \[self.windowmakeKeyAndVisible\];

returnYES;

}

