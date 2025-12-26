cc_library(
    name = "flecs",
    visibility = ["//visibility:public"],
    defines = ["flecs_EXPORTS"],

    srcs = glob(["src/**/*.c", "src/**/*.h", "src/**/*.inl"]),
    hdrs = glob(["include/**/*.h", "include/**/*.hpp", "include/**/*.inl"]),
    includes = ["include"],
)

/*
Benchmark                              Measurement
baseline                               0.67      
get_id_not_found                       0.50      
get                                    0.18      
get_pair                               0.43      
get_inherited_depth_1                  0.13      
get_inherited_depth_2                  0.31      
get_inherited_depth_16                 0.20      
get_mut_not_found                      0.29      
get_mut                                0.22      
get_mut_sparse                         0.15      
get_mut_dont_fragment                  0.14      
get_sparse_not_found                   0.13      
get_sparse                             0.49      
get_target_not_found                   0.36      
get_target                             0.65      
get_target_dont_fragment               0.25      
get_target_dont_fragment_exclusive     1.63      
get_parent_not_found                   1.05      
get_parent                             0.17
*/


/*
Benchmark                              Measurement
baseline                               0.68      
get_id_not_found                       0.41      
get                                    0.17      
get_pair                               0.41      
get_inherited_depth_1                  0.36      
get_inherited_depth_2                  0.14      
get_inherited_depth_16                 0.17      
get_mut_not_found                      0.12      
get_mut                                0.13      
get_mut_sparse                         0.33      
get_mut_dont_fragment                  6.36      
get_sparse_not_found                   0.48      
get_sparse                             0.15      
get_target_not_found                   0.18      
get_target                             0.13      
get_target_dont_fragment               0.13      
get_target_dont_fragment_exclusive     0.29      
get_parent_not_found                   0.12      
get_parent                             0.15
*/


