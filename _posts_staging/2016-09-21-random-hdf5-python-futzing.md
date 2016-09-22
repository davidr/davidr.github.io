---
layout: post
title:  "In which David learns about HDF5"
date:   2016-09-21 23:14:20 -0500
categories: [python, hdf5, h5py, mpi, HPC]
---

**Problem:**

There's data out there in the world, and I want it in a format that's as efficient as possible
for HPC uses, but I don't want to have to invent my own serialization format. HDF5 seems like
it has the right stuff, but it's not super clear to me exactly how to go from a "normal" data
set (columns of multiple types of data, *e.g.* Timestamp, Event ID, User Name).
