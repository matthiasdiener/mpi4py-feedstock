About mpi4py
============

Home: https://mpi4py.github.io/

Package license: BSD-2-Clause

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/mpi4py-feedstock/blob/master/LICENSE.txt)

Summary: Python bindings for MPI

Development: https://github.com/mpi4py/mpi4py

Documentation: https://mpi4py.readthedocs.org/

MPI for Python provides bindings of the Message Passing Interface (MPI)
standard for the Python programming language, allowing any Python program
to exploit multiple processors.


Current build status
====================


<table><tr>
    <td>Travis</td>
    <td>
      <a href="https://travis-ci.com/conda-forge/mpi4py-feedstock">
        <img alt="macOS" src="https://img.shields.io/travis/com/conda-forge/mpi4py-feedstock/master.svg?label=macOS">
      </a>
    </td>
  </tr><tr>
    <td>Drone</td>
    <td>
      <a href="https://cloud.drone.io/conda-forge/mpi4py-feedstock">
        <img alt="linux" src="https://img.shields.io/drone/build/conda-forge/mpi4py-feedstock/master.svg?label=Linux">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_mpimpichpython3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_64_mpimpichpython3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpimpichpython3.7.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_64_mpimpichpython3.7.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpimpichpython3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_64_mpimpichpython3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpimpichpython3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_64_mpimpichpython3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpimpichpython3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_64_mpimpichpython3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpiopenmpipython3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_64_mpiopenmpipython3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpiopenmpipython3.7.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_64_mpiopenmpipython3.7.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpiopenmpipython3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_64_mpiopenmpipython3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpiopenmpipython3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_64_mpiopenmpipython3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpiopenmpipython3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_64_mpiopenmpipython3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpimpichpython3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_mpimpichpython3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpimpichpython3.7.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_mpimpichpython3.7.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpimpichpython3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_mpimpichpython3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpimpichpython3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_mpimpichpython3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpimpichpython3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_mpimpichpython3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpiopenmpipython3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_mpiopenmpipython3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpiopenmpipython3.7.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_mpiopenmpipython3.7.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpiopenmpipython3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_mpiopenmpipython3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpiopenmpipython3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_mpiopenmpipython3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpiopenmpipython3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_mpiopenmpipython3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpimpichpython3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_mpimpichpython3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpimpichpython3.7.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_mpimpichpython3.7.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpimpichpython3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_mpimpichpython3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpimpichpython3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_mpimpichpython3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpimpichpython3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_mpimpichpython3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpiopenmpipython3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_mpiopenmpipython3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpiopenmpipython3.7.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_mpiopenmpipython3.7.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpiopenmpipython3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_mpiopenmpipython3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpiopenmpipython3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_mpiopenmpipython3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpiopenmpipython3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_mpiopenmpipython3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpimpichpython3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_64_mpimpichpython3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpimpichpython3.7.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_64_mpimpichpython3.7.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpimpichpython3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_64_mpimpichpython3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpimpichpython3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_64_mpimpichpython3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpimpichpython3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_64_mpimpichpython3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpiopenmpipython3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_64_mpiopenmpipython3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpiopenmpipython3.7.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_64_mpiopenmpipython3.7.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpiopenmpipython3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_64_mpiopenmpipython3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpiopenmpipython3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_64_mpiopenmpipython3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpiopenmpipython3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_64_mpiopenmpipython3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpimpichpython3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_mpimpichpython3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpimpichpython3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_mpimpichpython3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpimpichpython3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_mpimpichpython3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpiopenmpipython3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_mpiopenmpipython3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpiopenmpipython3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_mpiopenmpipython3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpiopenmpipython3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_mpiopenmpipython3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=win&configuration=win_64_python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.7.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=win&configuration=win_64_python3.7.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=win&configuration=win_64_python3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=win&configuration=win_64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=644&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mpi4py-feedstock?branchName=master&jobName=win&configuration=win_64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-mpi4py-green.svg)](https://anaconda.org/conda-forge/mpi4py) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/mpi4py.svg)](https://anaconda.org/conda-forge/mpi4py) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/mpi4py.svg)](https://anaconda.org/conda-forge/mpi4py) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/mpi4py.svg)](https://anaconda.org/conda-forge/mpi4py) |

Installing mpi4py
=================

Installing `mpi4py` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `mpi4py` can be installed with:

```
conda install mpi4py
```

It is possible to list all of the versions of `mpi4py` available on your platform with:

```
conda search mpi4py --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating mpi4py-feedstock
=========================

If you would like to improve the mpi4py recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/mpi4py-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@SylvainCorlay](https://github.com/SylvainCorlay/)
* [@dalcinl](https://github.com/dalcinl/)
* [@davidbrochart](https://github.com/davidbrochart/)
* [@leofang](https://github.com/leofang/)
* [@minrk](https://github.com/minrk/)
* [@msarahan](https://github.com/msarahan/)
* [@ocefpaf](https://github.com/ocefpaf/)

