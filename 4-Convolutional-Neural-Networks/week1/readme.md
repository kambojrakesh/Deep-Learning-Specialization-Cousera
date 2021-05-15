Zero-padding benefits:-<br><br>

	The main benefits of padding are:<br>

	1. It allows you to use a CONV layer without necessarily shrinking the height and width of the volumes. This is important for building deeper networks, since otherwise the   height/width would shrink as you go to deeper layers. An important special case is the "same" convolution, in which the height/width is exactly preserved after one layer.
	<br>
	2. It helps us keep more of the information at the border of an image. Without padding, very few values at the next layer would be affected by pixels at the edges of an image.
	<br>
	use of np.pad</br>
	a = np.pad(a, ((0,0), (1,1), (0,0), (3,3), (0,0)), mode='constant', constant_values = (0,0))</br>
	</br>
	</br>
	</br>
	</br>
	
	</br>
	
	</br>
	</br>