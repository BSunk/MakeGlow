# MakeGlow
Library that adds a glow effect to VectorDrawables or BitmapDrawables

## Add to build.gradle

    compile 'com.bsunk.makeglow:makeglow:1.0.0'
    
 <img src="/screenshots/Screenshot_20170301-140437.png" alt="image" width="300">
 <img src="/screenshots/Screenshot_20170301-140444.png" alt="image" width="300">
 <img src="/screenshots/Screenshot_20170301-140454.png" alt="image" width="300">

## Attributes

        <attr name="drawable" format="reference" />
        <attr name="glowColor" format="color"/>
        <attr name="glowRadius" format="integer"/>
        <attr name="glowOff" format="boolean"/>
        <attr name="glowOffColor" format="color"/>
        <attr name="blurFilter" format="integer"/>

## Some info
        The attribute 'drawable' expects the source you want to glow.
        
        The attribute 'blurfilter' can be 0,1,2, or 3.
        0-BlurMaskFilter.Blur.INNER
        1-BlurMaskFilter.Blur.OUTER
        2-BlurMaskFilter.Blur.NORMAL
        3-BlurMaskFilter.Blur.SOLID

License
-------

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
