add_subdirectory(BrainF)
add_subdirectory(Fibonacci)
add_subdirectory(HowToUseJIT)
add_subdirectory(Kaleidoscope)
add_subdirectory(ModuleMaker)

add_subdirectory(vex_llc)
add_subdirectory(vex-desc)
add_subdirectory(DFA)

if( NOT WIN32 )
    add_subdirectory(ExceptionDemo)
endif()

if( HAVE_PTHREAD_H )
  add_subdirectory(ParallelJIT)
endif( HAVE_PTHREAD_H )
