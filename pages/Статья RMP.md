- {{embed [[@Riemannian Motion Policies]]}}
- # #Заметки
	- Идея, видимо, заимствовать идею "построения пути в операционном пространстве и взятия псевдообратной матрицы для возврата в конфигурационное". Только подменяя операцию псевдообращения на более геометрический [[pullback]].
		- > In practice, it is common to transform behaviors described as dynamical systems on multiple task spaces (especially the end-effector space) into the C-space using pseudoinverses and to combine the resulting policies by superimposing them.
		-
	- По факту политика заключается в поиске $f\;:\; q, \dot{q} \mapsto \ddot{q}$, иначе говоря в формировании по положению и скорости сочленений их ускорения.
	  id:: 67a48515-274d-4271-8b6e-8abd92cbd787
	  Но предлагают в зависимости от того, чем хотим управлять, пересчитывать из метода Эйлера позиции и скорости.
	  > ![image.png](../assets/image_1738691346372_0.png)
	- Нашел [реализацию](https://docs.omniverse.nvidia.com/isaacsim/latest/advanced_tutorials/tutorial_motion_generation_rmpflow.html) в симуляции в `Isaac sim`
- # #Вопросы
	-
- # #Мысли
	-
- # #Выводы
-