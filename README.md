# three-mixamo
basic exemple of mixamo character integration with three.js\
with controls, appearance, animations

Method used:\
-Inside any 3D app: chain all animations on a single skeleton/timeline\
-skin all meshes on this skeleton, doesn’t matter if meshes stack on each other\
-With three.js code, split your timeline using THREE.AnimationUtils.subclip function\
-Hide/show/mix the correct meshes and animations

<a href="https://raw.githack.com/Oxynt/three-mixamo/main/">DEMO</a>
