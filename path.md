	path=untar_data(URLs.MNIST_SAMPLE)
	path
('C:/Users/panag/.fastai/data/mnist_sample')

where untar_data downloads and decompresses data from the link


	Path.BASE_PATH=path
sets path to be the base path : path = ' . '

where Path is pathlib.Path

	path.ls()
Shows the content of the folder