# pygame-create-map-array
pygame-create-map-array is a tool which can be used to return an list of tile(numbers) from a tiled map for creating lists for colision detection; for example tiles which are walkable or not. This was inspired from a pygame programming tutorial by Will Smith on Udemy. He used a base tiled map image as a background image for his game and overlayed a numbered 2D tile matrix in order to get the tile numbers and other associated attributes with the tiles which can be used within the game for player movement AI enemy attacks etc. The problem was that you needed to calculate manually the tiles which were walkable etc and add these to an array.
This tool allows you to bring in an image file and overlay the appropiate grid matrix and by mouse clicking the tiles on the image which are to be included in the no walk zones for example, the tool will return a list of the tile numbers. This can then be either imported or just copy and paste the list into your game code. (see code below). This saves counting manually the tiles.

def obstacles():
	obstacle_map = [32, 33, 34, 35, 36]
	return obstacle_map
