+++
title = "`void hook_result_copy_construction(T *, U &&) noexcept`"
description = "ADL discovered free function hook invoked by the converting copy constructors of `basic_result`."
+++

One of the constructor hooks for {{% api "basic_result<T, E, NoValuePolicy>" %}}, generally invoked by the converting copy constructors of `basic_result` (NOT the standard copy constructor). See each constructor's documentation to see which specific hook it invokes.

*Overridable*: By Argument Dependent Lookup.

*Requires*: Nothing.

*Namespace*: `BOOST_OUTCOME_V2_NAMESPACE::hooks`

*Header*: `<boost/outcome/basic_result.hpp>`
