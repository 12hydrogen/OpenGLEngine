# A Simple Engine using OpenGL as Backend

## Intro

This is a simple processing program that recieve configuration and models to create a simple 3D graphic output.

## What it will do
- Set up a basic enviroument for render progress.
- Recieve informations about render progress such as models, config and shader code.
- Print the render result in a single window.

## What should provide to it
- Config that specified the position of the rest data.
- Models in many forms, including a plain vertices array with primitive setted and a optional indices array, for render progress.
- Usage of models that specified the following information.
	- Relative postion of certain model.
	- The lighting property.
- Some complete sets of shader program code.

## What it will provide to assist rendering
- A interface to control render pipeline, including.
	- Uniforms.
	- Transform Materixs.
	- Customizable render loop.
- A Python resolver and proper environment to further extent customizable content, containing.
	- Proper tool function to operate OpenGL math culcalate.
	- Ability to insert code snippets into customizable content.
