

1.Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-20.04"
  config.vm.box_download_insecure=true
  end


   ![image](https://user-images.githubusercontent.com/97973917/218808319-ebc4b3e6-d063-4eb8-954b-7aed14980fc6.png)

2. ![image](https://user-images.githubusercontent.com/97973917/218808480-8124a724-82fc-433d-ba56-a6e3ac2066de.png)



3.config.vm.provider "virtualbox" do |v|
  v.memory = []
  v.cpus = []
  end



4. ![image](https://user-images.githubusercontent.com/97973917/218809328-7c0a1087-671c-4571-a8ea-c60eee7a2bb2.png)




5.1.HISTFILESIZE - максимальное число строк в файле истории для сохранения, строка 1155

![image](https://user-images.githubusercontent.com/97973917/218821522-c994741c-5e7e-422b-a25a-62d418a42a01.png)




5.2.ignoreboth — не записывать команду, которая начинается с пробела, либо команду, которая дублирует предыдущую.




6. {} могут использоваться для одновременного создания нескольких директорий\файлов, а так же для описания пути одновременно к нескольким файлам, расположенным по одному пути.
man bash - раздел RESERVED WORDS 

![image](https://user-images.githubusercontent.com/97973917/218823950-4a9c0573-1175-4983-a119-d01455627bdc.png)




7. touch {000001..100000}.[расширениефайла] 
![image](https://user-images.githubusercontent.com/97973917/218825067-3f3340fd-5268-4573-adda-947f92916db2.png)
 
 
 
8. 1.![image](https://user-images.githubusercontent.com/97973917/218827960-7afea56f-8ba3-42b7-bcea-a77604ca9be4.png)

   2.Проверяет наличие директории tmp

9. ![image](https://user-images.githubusercontent.com/97973917/218831073-24314eda-2646-4fec-b4a2-ce90b30d64dd.png)

10. at - Используется для назначения одноразового задания на заданное время
batch - Используется для назначения одноразовых задач, которые должны выполняться, когда загрузка системы становится 0,8 (0,5)

