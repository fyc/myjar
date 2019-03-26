# myjar
打包自定义包名的jar包，以okhttp示例（需要配合jyokio.jar）okhttp的代码基于3.10.x，而jyokio是基于1.14.1<br>
但好像打aar有效，而打jar无效，jar只能从aar里面解压出来，才可以用（//todo）
1,执行assemble命令，在build/outputs中生成aar
2，改后缀为zip，解压得到里面的class.jar,即是我们想要的okhttp.jar了，改个名字就可以用了


