EdgeDetection
=============

Detección de bordes utilizando PCL y Openni / Edge Detection using PCL and OpenNi / Kantenerkennung mit PCL und Openni

Si Error/ If Error/ Wenn Fehler:

terminate called after throwing an instance of ‘pcl::PCLIOException’ what(): No matching device found. openni_wrapper::OpenNIDevice::OpenNIDevice(xn::Context&, const xn::NodeInfo&, const xn::NodeInfo&, const xn::NodeInfo&, const xn::NodeInfo&) @ /home/andreas/pcl/pcl/trunk/io/src/openni_camera/openni_device.cpp @ 96 : creating depth generator failed. Reason: The network connection has been closed!

En linea de comando Linux / In Linux command line / In Linux-Befehlszeile:

   - Para obtener el puerto USB asociado a la cámara / To get USB camera port / Auf USB-Kamera-Anschluss bekommen: lsusb -
   - Permisos de ejecución a Kinect / Execution permissions for Kinect / Ausführung Berechtigungen für Kinect:  sudo chmod o+w /dev/bus/usb/001/012
