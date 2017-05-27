# Git – the POC. I am new to Git and Publishing code
To get started on Git with relevant content, first I need to practice on the basic method used there.

This project contains an empty Visual Studio Command line tool solution, build with Visual Studio 2017. The command line tool if for reference only. The future projects I plan to publish on Git will be build with Visual Studio, and therefore having a Visual Studio solution as part of the Git repository was important.

## Sharing code is heroic – but without documentation, of little use

Therefore, exploring on the basic method of adding documentation is an important part of my POC. I need to know how to easy organize text and images as part of the documentation, and even how to show code fragments for clarification of details.

## Simple strucutre, #[# n times] already demonstrated and will map to <h[n]></h[n]>

### Unordered lists

* Un-Ordered list item 1
* Un-Ordered list item 2
  * and sub element 2.1
  * and sub element 2.2
* Un-ordered list item 3

### ordered list

1. And ordered list
1. with several lines
   1. And sub elements
   1. again
1. and more

### Code, here we look at javascript

```javascript
function() {
	return true;
}
```


### Code, C# here
```c#
public class Demo 
{
	public const string x = "the x const";
}
```

### Link to source of knowledge

We don’t invent everything our self, and topic shared with high quality somewhere else should be acknowledge. In such case linking out of the repository without leaving is important.
Most of this help comes from:

[Mastering markdown](https://guides.github.com/features/mastering-markdown/ target="_blank")


### And finally an image, where the image is hosted within my the repository

![test an image](https://raw.githubusercontent.com/kip-dk/Poc/master/Documentation/c1.png)


I think I am good to go now. At least i will try.
