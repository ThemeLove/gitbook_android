
	1.Bitmap 和File 互转
     	序列化：主要用到bitmap对象的compress方法
		FileOutputStream fos = new FileOutputStream(path);
    	bitmap.compress(Bitmap.CompressFormat.PNG, 100, fos);
		反序列化：主要用到BitmapFactory类
		FileInputStream fis = new FileInputStream(imageCacheFile);
        BitmapFactory.decodeStream(fis);    
	2.
	