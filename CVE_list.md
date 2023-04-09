CVE issues from [mitre.org](https://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=HDF5)

| Issue # | Description |
|---------|-------------|
|[CVE-2022-26061](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-26061)|A heap-based buffer overflow vulnerability exists in the gif2h5 functionality of HDF5 Group libhdf5 1.10.4. A specially-crafted GIF file can lead to code execution. An attacker can provide a malicious file to trigger this vulnerability.|
|CVE-2022-25972|An out-of-bounds write vulnerability exists in the gif2h5 functionality of HDF5 Group libhdf5 1.10.4. A specially-crafted GIF file can lead to code execution. An attacker can provide a malicious file to trigger this vulnerability.|
|CVE-2022-25942|An out-of-bounds read vulnerability exists in the gif2h5 functionality of HDF5 Group libhdf5 1.10.4. A specially-crafted GIF file can lead to code execution. An attacker can provide a malicious file to trigger this vulnerability.|
|CVE-2021-46244|A Divide By Zero vulnerability exists in HDF5 v1.13.1-1 vis the function H5T__complete_copy () at /hdf5/src/H5T.c. This vulnerability causes an aritmetic exception, leading to a Denial of Service (DoS).|
|CVE-2021-46243|An untrusted pointer dereference vulnerability exists in HDF5 v1.13.1-1 via the function H5O__dtype_decode_helper () at hdf5/src/H5Odtype.c. This vulnerability can lead to a Denial of Service (DoS).|
|CVE-2021-46242|HDF5 v1.13.1-1 was discovered to contain a heap-use-after free via the component H5AC_unpin_entry.|
|CVE-2021-45833|A Stack-based Buffer Overflow Vulnerability exists in HDF5 1.13.1-1 via the H5D__create_chunk_file_map_hyper function in /hdf5/src/H5Dchunk.c, which causes a Denial of Service (context-dependent).|
|CVE-2021-45832|A Stack-based Buffer Overflow Vulnerability exists in HDF5 1.13.1-1 at at hdf5/src/H5Eint.c, which causes a Denial of Service (context-dependent).|
|CVE-2021-45830|A heap-based buffer overflow vulnerability exists in HDF5 1.13.1-1 via H5F_addr_decode_len in /hdf5/src/H5Fint.c, which could cause a Denial of Service.|
|CVE-2021-45829|HDF5 1.13.1-1 is affected by: segmentation fault, which causes a Denial of Service.|
|CVE-2021-37501|Buffer Overflow vulnerability in HDFGroup hdf5-h5dump 1.12.0 through 1.13.0 allows attackers to cause a denial of service via h5tools_str_sprint in /hdf5/tools/lib/h5tools_str.c.|
|CVE-2021-36977|matio (aka MAT File I/O Library) 1.5.20 and 1.5.21 has a heap-based buffer overflow in H5MM_memcpy (called from H5MM_malloc and H5C_load_entry), related to use of HDF5 1.12.0.|
|CVE-2021-31009|Multiple issues were addressed by removing HDF5. This issue is fixed in iOS 15.2 and iPadOS 15.2, macOS Monterey 12.1. Multiple issues in HDF5.|
|CVE-2020-10812|An issue was discovered in HDF5 through 1.12.0. A NULL pointer dereference exists in the function H5F_get_nrefs() located in H5Fquery.c. It allows an attacker to cause Denial of Service.|
|CVE-2020-10811|An issue was discovered in HDF5 through 1.12.0. A heap-based buffer over-read exists in the function H5O__layout_decode() located in H5Olayout.c. It allows an attacker to cause Denial of Service.|
|CVE-2020-10810|An issue was discovered in HDF5 through 1.12.0. A NULL pointer dereference exists in the function H5AC_unpin_entry() located in H5AC.c. It allows an attacker to cause Denial of Service.|
|CVE-2020-10809|An issue was discovered in HDF5 through 1.12.0. A heap-based buffer overflow exists in the function Decompress() located in decompress.c. It can be triggered by sending a crafted file to the gif2h5 binary. It allows an attacker to cause Denial of Service.|
|CVE-2019-9152|An issue was discovered in the HDF HDF5 1.10.4 library. There is an out of bounds read in the function H5MM_xstrdup in H5MM.c when called from H5O_dtype_decode_helper in H5Odtype.c.|
|CVE-2019-9151|An issue was discovered in the HDF HDF5 1.10.4 library. There is an out of bounds read in the function H5VM_memcpyvv in H5VM.c when called from H5D__compact_readvv in H5Dcompact.c.|
|CVE-2019-8398|An issue was discovered in the HDF HDF5 1.10.4 library. There is an out of bounds read in the function H5T_get_size in H5T.c.|
|CVE-2019-8397|An issue was discovered in the HDF HDF5 1.10.4 library. There is an out of bounds read in the function H5T_close_real in H5T.c.|
|CVE-2019-8396|A buffer overflow in H5O__layout_encode in H5Olayout.c in the HDF HDF5 through 1.10.4 library allows attackers to cause a denial of service via a crafted HDF5 file. This issue was triggered while repacking an HDF5 file, aka "Invalid write of size 2."|
|CVE-2018-17439|An issue was discovered in the HDF HDF5 1.10.3 library. There is a stack-based buffer overflow in the function H5S_extent_get_dims() in H5S.c. Specifically, this issue occurs while converting an HDF5 file to a GIF file.|
|CVE-2018-17438|A SIGFPE signal is raised in the function H5D__select_io() of H5Dselect.c in the HDF HDF5 through 1.10.3 library during an attempted parse of a crafted HDF file, because of incorrect protection against division by zero. It could allow a remote denial of service attack.|
|CVE-2018-17437|Memory leak in the H5O_dtype_decode_helper() function in H5Odtype.c in the HDF HDF5 through 1.10.3 library allows attackers to cause a denial of service (memory consumption) via a crafted HDF5 file.|
|CVE-2018-17436|ReadCode() in decompress.c in the HDF HDF5 through 1.10.3 library allows attackers to cause a denial of service (invalid write access) via a crafted HDF5 file. This issue was triggered while converting a GIF file to an HDF file.|
|CVE-2018-17435|A heap-based buffer over-read in H5O_attr_decode() in H5Oattr.c in the HDF HDF5 through 1.10.3 library allows attackers to cause a denial of service via a crafted HDF5 file. This issue was triggered while converting an HDF file to GIF file.|
|CVE-2018-17434|A SIGFPE signal is raised in the function apply_filters() of h5repack_filters.c in the HDF HDF5 through 1.10.3 library during an attempted parse of a crafted HDF file, because of incorrect protection against division by zero. It could allow a remote denial of service attack.|
|CVE-2018-17433|A heap-based buffer overflow in ReadGifImageDesc() in gifread.c in the HDF HDF5 through 1.10.3 library allows attackers to cause a denial of service via a crafted HDF5 file. This issue was triggered while converting a GIF file to an HDF file.|
|CVE-2018-17432|A NULL pointer dereference in H5O_sdspace_encode() in H5Osdspace.c in the HDF HDF5 through 1.10.3 library allows attackers to cause a denial of service via a crafted HDF5 file.|
|CVE-2018-17237|A SIGFPE signal is raised in the function H5D__chunk_set_info_real() of H5Dchunk.c in the HDF HDF5 1.10.3 library during an attempted parse of a crafted HDF file, because of incorrect protection against division by zero. This issue is different from CVE-2018-11207.|
|CVE-2018-17234|Memory leak in the H5O__chunk_deserialize() function in H5Ocache.c in the HDF HDF5 through 1.10.3 library allows attackers to cause a denial of service (memory consumption) via a crafted HDF5 file.|
|CVE-2018-17233|A SIGFPE signal is raised in the function H5D__create_chunk_file_map_hyper() of H5Dchunk.c in the HDF HDF5 through 1.10.3 library during an attempted parse of a crafted HDF file, because of incorrect protection against division by zero. It could allow a remote denial of service attack.|
|CVE-2018-16438|An issue was discovered in the HDF HDF5 1.8.20 library. There is an out of bounds read in H5L_extern_query at H5Lexternal.c.|
|CVE-2018-15671|An issue was discovered in the HDF HDF5 1.10.2 library. Excessive stack consumption has been detected in the function H5P__get_cb() in H5Pint.c during an attempted parse of a crafted HDF file. This results in denial of service.|
|CVE-2018-14460|An issue was discovered in the HDF HDF5 1.8.20 library. There is a heap-based buffer over-read in the function H5O_sdspace_decode in H5Osdspace.c.|
|CVE-2018-14035|An issue was discovered in the HDF HDF5 1.8.20 library. There is a heap-based buffer over-read in the function H5VM_memcpyvv in H5VM.c.|
|CVE-2018-14034|An issue was discovered in the HDF HDF5 1.8.20 library. There is an out of bounds read in the function H5O_pline_reset in H5Opline.c.|
|CVE-2018-14033|An issue was discovered in the HDF HDF5 1.8.20 library. There is a heap-based buffer over-read in the function H5O_layout_decode in H5Olayout.c, related to HDmemcpy.|
|CVE-2018-14031|An issue was discovered in the HDF HDF5 1.8.20 library. There is a heap-based buffer over-read in the function H5T_copy in H5T.c.|
|CVE-2018-13876|An issue was discovered in the HDF HDF5 1.8.20 library. There is a stack-based buffer overflow in the function H5FD_sec2_read in H5FDsec2.c, related to HDread.|
|CVE-2018-13875|An issue was discovered in the HDF HDF5 1.8.20 library. There is an out-of-bounds read in the function H5VM_memcpyvv in H5VM.c.|
|CVE-2018-13874|An issue was discovered in the HDF HDF5 1.8.20 library. There is a stack-based buffer overflow in the function H5FD_sec2_read in H5FDsec2.c, related to HDmemset.|
|CVE-2018-13873|An issue was discovered in the HDF HDF5 1.8.20 library. There is a buffer over-read in H5O_chunk_deserialize in H5Ocache.c.|
|CVE-2018-13872|An issue was discovered in the HDF HDF5 1.8.20 library. There is a heap-based buffer overflow in the function H5G_ent_decode in H5Gent.c.|
|CVE-2018-13871|An issue was discovered in the HDF HDF5 1.8.20 library. There is a heap-based buffer overflow in the function H5FL_blk_malloc in H5FL.c.|
|CVE-2018-13870|An issue was discovered in the HDF HDF5 1.8.20 library. There is a heap-based buffer over-read in the function H5O_link_decode in H5Olink.c.|
|CVE-2018-13869|An issue was discovered in the HDF HDF5 1.8.20 library. There is a memcpy parameter overlap in the function H5O_link_decode in H5Olink.c.|
|CVE-2018-13868|An issue was discovered in the HDF HDF5 1.8.20 library. There is a heap-based buffer over-read in the function H5O_fill_old_decode in H5Ofill.c.|
|CVE-2018-13867|An issue was discovered in the HDF HDF5 1.8.20 library. There is an out of bounds read in the function H5F__accum_read in H5Faccum.c.|
|CVE-2018-13866|An issue was discovered in the HDF HDF5 1.8.20 library. There is a stack-based buffer over-read in the function H5F_addr_decode_len in H5Fint.c.|
|CVE-2018-11207|A division by zero was discovered in H5D__chunk_init in H5Dchunk.c in the HDF HDF5 1.10.2 library. It could allow a remote denial of service attack.|
|CVE-2018-11206|An out of bounds read was discovered in H5O_fill_new_decode and H5O_fill_old_decode in H5Ofill.c in the HDF HDF5 1.10.2 library. It could allow a remote denial of service or information disclosure attack.|
|CVE-2018-11205|A out of bounds read was discovered in H5VM_memcpyvv in H5VM.c in the HDF HDF5 1.10.2 library. It could allow a remote denial of service or information disclosure attack.|
|CVE-2018-11204|A NULL pointer dereference was discovered in H5O__chunk_deserialize in H5Ocache.c in the HDF HDF5 1.10.2 library. It could allow a remote denial of service attack.|
|CVE-2018-11203|A division by zero was discovered in H5D__btree_decode_key in H5Dbtree.c in the HDF HDF5 1.10.2 library. It could allow a remote denial of service attack.|
|CVE-2018-11202|A NULL pointer dereference was discovered in H5S_hyper_make_spans in H5Shyper.c in the HDF HDF5 1.10.2 library. It could allow a remote denial of service attack.|
|CVE-2017-17509|In HDF5 1.10.1, there is an out of bounds write vulnerability in the function H5G__ent_decode_vec in H5Gcache.c in libhdf5.a. For example, h5dump would crash or possibly have unspecified other impact someone opens a crafted hdf5 file.|
|CVE-2017-17508|In HDF5 1.10.1, there is a divide-by-zero vulnerability in the function H5T_set_loc in the H5T.c file in libhdf5.a. For example, h5dump would crash when someone opens a crafted hdf5 file.|
|CVE-2017-17507|In HDF5 1.10.1, there is an out of bounds read vulnerability in the function H5T_conv_struct_opt in H5Tconv.c in libhdf5.a. For example, h5dump would crash when someone opens a crafted hdf5 file.|
|CVE-2017-17506|In HDF5 1.10.1, there is an out of bounds read vulnerability in the function H5Opline_pline_decode in H5Opline.c in libhdf5.a. For example, h5dump would crash when someone opens a crafted hdf5 file.|
|CVE-2017-17505|In HDF5 1.10.1, there is a NULL pointer dereference in the function H5O_pline_decode in the H5Opline.c file in libhdf5.a. For example, h5dump would crash when someone opens a crafted hdf5 file.|
|CVE-2016-4333|The HDF5 1.8.16 library allocating space for the array using a value from the file has an impact within the loop for initializing said array allowing a value within the file to modify the loop's terminator. Due to this, an aggressor can cause the loop's index to point outside the bounds of the array when initializing it.|
|CVE-2016-4332|The library's failure to check if certain message types support a particular flag, the HDF5 1.8.16 library will cast the structure to an alternative structure and then assign to fields that aren't supported by the message type and the library will write outside the bounds of the heap buffer. This can lead to code execution under the context of the library.|
|CVE-2016-4331|When decoding data out of a dataset encoded with the H5Z_NBIT decoding, the HDF5 1.8.16 library will fail to ensure that the precision is within the bounds of the size leading to arbitrary code execution.|
|CVE-2016-4330|In the HDF5 1.8.16 library's failure to check if the number of dimensions for an array read from the file is within the bounds of the space allocated for it, a heap-based buffer overflow will occur, potentially leading to arbitrary code execution.|