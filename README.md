# JpgCode
compress jpg picture file or the buffer of picture
If you want to compress a jpg file ,you can call API of jpeg_stdio_src (j_decompress_ptr cinfo, FILE * infile).If you have read jpg 
file into buffer, you can call API of jpeg_stdio_buffer_src (j_decompress_ptr cinfo, UINT8 *buffer, long size).
