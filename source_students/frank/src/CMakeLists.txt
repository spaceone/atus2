#find_library( PNG_LIBRARY NAMES png PATHS ENV LD_LIBRARY_PATH DEFAULT_PATH )

#ADD_EXECUTABLE( mm2png mm2png.cpp pngwriter.cc)
#TARGET_LINK_LIBRARIES( mm2png myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} ${PNG_LIBRARY} )

ADD_EXECUTABLE( noise_solver noise_solver.cpp )
TARGET_LINK_LIBRARIES( noise_solver myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( reduce_data reduce_data.cpp )
TARGET_LINK_LIBRARIES( reduce_data myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

#ADD_EXECUTABLE( lis_sg_test_3 lis_sg_test_3.cpp )
#TARGET_LINK_LIBRARIES( lis_sg_test_3 myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( noise_int_demo noise_int_demo.cpp )
TARGET_LINK_LIBRARIES( noise_int_demo myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( noise_int_demo_B noise_int_demo_B.cpp )
TARGET_LINK_LIBRARIES( noise_int_demo_B myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( noise_gen noise_gen.cpp )
TARGET_LINK_LIBRARIES( noise_gen myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( sine_gen sine_gen.cpp )
TARGET_LINK_LIBRARIES( sine_gen myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( psd psd.cpp )
TARGET_LINK_LIBRARIES( psd myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( compare_data compare_data.cpp )
TARGET_LINK_LIBRARIES( compare_data myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( diff_data diff_data.cpp )
TARGET_LINK_LIBRARIES( diff_data myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( prob_dist prob_dist.cpp )
TARGET_LINK_LIBRARIES( prob_dist myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( spread_1d spread_1d.cpp )
TARGET_LINK_LIBRARIES( spread_1d myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( interpol_chirp interpol_chirp.cpp )
TARGET_LINK_LIBRARIES( interpol_chirp myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( noise_coeff noise_coeff.cpp )
TARGET_LINK_LIBRARIES( noise_coeff myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( autocorrelate_data autocorrelate_data.cpp )
TARGET_LINK_LIBRARIES( autocorrelate_data myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( integrate_data integrate_data.cpp )
TARGET_LINK_LIBRARIES( integrate_data myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( integrate_noise integrate_noise.cpp )
TARGET_LINK_LIBRARIES( integrate_noise myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( reverse_data reverse_data.cpp )
TARGET_LINK_LIBRARIES( reverse_data myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )

ADD_EXECUTABLE( unpack_seq unpack_seq.cpp )
TARGET_LINK_LIBRARIES( unpack_seq myutils ${GSL_LIBRARY_1} ${GSL_LIBRARY_2} m ${MUPARSER_LIBRARY} ${LIS_LIBRARY} )
